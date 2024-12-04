# NLP-Lab4
The main purpose behind this lab is to get familiar with NLP language models.

## Part 1

This project aims to build and evaluate language models for classifying and regressing medical text data obtained from Arabic websites. The process involves web scraping, preprocessing, training various recurrent neural network (RNN) architectures, and evaluating model performance.

### Data Collection

We obtained text data from [Webteb](https://www.webteb.com/neurology/diseases), a website focusing on medical information. Using web scraping libraries like BeautifulSoup, we collected information about various diseases in Arabic language from the neurology section.

### Text Scoring

We assigned scores to each text based on its relevance to the medical field. A rule-based scoring function was developed, assigning points depending on the presence of specific medical terms and keywords related to neurology.

### Preprocessing Pipeline

A preprocessing pipeline was established to clean and prepare the collected dataset for training. This pipeline includes tokenization, stemming, lemmatization, removal of stop words, and discretization.

### Model Training

We trained four different recurrent neural network (RNN) architectures: Simple RNN, Bidirectional RNN, GRU (Gated Recurrent Unit), and LSTM (Long Short-Term Memory). Hyperparameters were tuned to optimize model performance.

### Model Evaluation

The trained models were evaluated using standard metrics such as loss and mean absolute error (MAE). Additionally, we computed the BLEU score, a metric commonly used in natural language processing tasks to evaluate the quality of generated text.

### Conclusion

The evaluation results indicate that the Bidirectional RNN model achieved the best performance among the tested architectures. However, further experimentation and fine-tuning of hyperparameters may be necessary to improve model accuracy. Overall, this project demonstrates the feasibility of using deep learning techniques for analyzing medical text data in Arabic language.
