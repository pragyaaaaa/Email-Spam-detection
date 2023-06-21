# Email-Spam-detection

This project involves building a spam classification model using the Naive Bayes algorithm. The dataset is preprocessed by removing null values and unnecessary columns. Text data is then preprocessed by tokenizing, removing stopwords and punctuation, and applying stemming. Additional features such as the number of characters, words, and sentences are computed. The model is trained using Multinomial Naive Bayes and evaluated using accuracy and precision scores.


## Requirements
To run the code, you need to have the following dependencies installed:

numpy

pandas

seaborn

matplotlib

scikit-learn

nltk

## Results
The script will output the accuracy and precision scores for the spam classification model.

## Model and Vectorizer
The trained model and TF-IDF vectorizer are saved in the following files:

model.pkl: The trained Multinomial Naive Bayes classifier.

vectorizer.pkl: The TF-IDF vectorizer.
