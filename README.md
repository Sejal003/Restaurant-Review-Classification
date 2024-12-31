# Restaurant-Review-Classification
![image](https://github.com/user-attachments/assets/5ec24696-1f95-4f85-8844-75678b87c239)

**Overview**
This project implements machine learning models to classify restaurant reviews as positive or negative using Natural Language Processing (NLP) techniques. The project compares the performance of Logistic Regression and Random Forest Classifier models using text preprocessing and Bag of Words vectorization.

**Dataset**
The project uses a TSV (Tab-Separated Values) file containing restaurant reviews and their corresponding sentiment labels.

**Dataset structure:**
Review text (string)
Sentiment label (positive/negative)

**Text Processing Pipeline**

**Data Cleaning**
Loading TSV data
Removing special characters
Converting text to lowercase

**Text Preprocessing**
Stopword removal using NLTK
Stemming for text normalization
Text tokenization

**Feature Engineering**
Converting text to numerical features using Bag of Words
Implementation using CountVectorizer from scikit-learn

**Model Development**
The project implements and compares two classification models:

**Logistic Regression**
Binary classification model
Linear decision boundary
Probability-based predictions

**Random Forest Classifier**
Ensemble learning method
Multiple decision trees
Voting-based classification

**Results**
Comparison of model performances:

**Accuracy scores**
Precision, Recall, F1-score
Confusion matrix for each model
