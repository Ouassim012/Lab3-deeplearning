# Lab3
The main purpose behind this lab is to get familiar with Pytorch, to build deep
neural network architecture for Natural language process by using Sequence Models.

## Part 1

This project aims to build and evaluate language models for classifying and regressing medical text data obtained from Arabic websites. The process involves web scraping, preprocessing, training various recurrent neural network (RNN) architectures, and evaluating model performance.

### Data Collection
The text data was sourced from [Webteb](https://www.webteb.com/neurology/diseases), a medical website offering information on neurological diseases in Arabic. We utilized web scraping tools like BeautifulSoup to extract relevant content from the neurology section.

### Text Scoring

A comprehensive preprocessing pipeline was designed to clean and prepare the dataset for model training. The pipeline includes:

Tokenization: Splitting text into individual words or tokens.
Stemming and Lemmatization: Reducing words to their root or base forms.
Stop Word Removal: Eliminating non-informative words.
Discretization: Converting continuous variables into categorical representations.

### Model Training

Model Training
We trained and compared the performance of four recurrent neural network (RNN) architectures:

Simple RNN: A basic recurrent network.
Bidirectional RNN: Processes input in both forward and backward directions.
GRU (Gated Recurrent Unit): A simplified version of LSTM with fewer parameters.
LSTM (Long Short-Term Memory): Designed to capture long-range dependencies in sequential data.
Hyperparameter tuning was performed to enhance model efficiency and performance.

### Model Evaluation

The models were evaluated using the following metrics:

Loss: Measures the prediction error during training.
Mean Absolute Error (MAE): Quantifies the difference between predicted and actual values.
BLEU Score: Used to assess the quality of generated text compared to reference text, commonly applied in NLP tasks.

### Results and insights

Among the tested architectures, the Bidirectional RNN exhibited the best overall performance, delivering superior accuracy and lower error rates. While these results are promising, additional experimentation and hyperparameter adjustments could further optimize model performance.

### Conclusion

This project successfully demonstrates the potential of RNN-based deep learning models for processing and analyzing Arabic medical text. The workflow from data collection to evaluation provides a robust framework for tackling similar NLP tasks, with room for future enhancements and exploration.
