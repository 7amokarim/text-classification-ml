# Text Classification Project

## Overview
In this project, two machine learning models, Logistic Regression and Naive Bayes, were implemented to perform text classification tasks.

Two datasets were used:
- IMDB Movie Reviews Dataset (for sentiment analysis)
- SMS Spam Dataset (for spam detection)

The goal was to compare the performance of both models on different types of text data.

---

## Dataset
The datasets were downloaded manually from Kaggle and loaded locally into the notebook.

- IMDB dataset contains movie reviews labeled as positive or negative.
- SMS dataset contains messages labeled as spam or ham.

---

## Preprocessing
The text data was preprocessed before training the models:

- Labels were converted into numerical values:
  - Positive / Spam → 1
  - Negative / Ham → 0
- The data was split into training and testing sets (80% training, 20% testing)
- TF-IDF vectorization was used to convert text into numerical features

---

## Models Used
Two models were trained and evaluated:

- Logistic Regression
- Naive Bayes (MultinomialNB)

Each model was applied to both datasets.

---

## Results
The performance of the models was evaluated using accuracy:

- Naive Bayes (SMS): 97.3%
- Logistic Regression (SMS): 95.7%
- Logistic Regression (IMDB): 88.8%
- Naive Bayes (IMDB): 85.0%

---

## Analysis
Naive Bayes achieved the best performance on the SMS dataset because the data is simple and contains short messages.

Logistic Regression performed better on the IMDB dataset because it can handle more complex and longer text more effectively.

---

## Run the Project
The notebook can be run directly using Google Colab:

[Open in Colab](https://colab.research.google.com/drive/1w80kPzbjcTxnNP0i4rvSIEhUbh6c0PpC?usp=sharing)

---

## Conclusion
This project shows that model performance depends on the nature of the dataset. Simpler models like Naive Bayes can perform very well on simple data, while Logistic Regression is more suitable for complex text data.
