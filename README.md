# Fake-News-Detection
 Objective:
To build a machine learning model that can automatically detect whether a news article is fake or real using textual data.

 Tools & Libraries Used:

Python

Pandas, Numpy

Scikit-learn

TfidfVectorizer

PassiveAggressiveClassifier

 Dataset:
Political/News dataset containing labeled real and fake news articles.

 Workflow:

Loaded and cleaned the dataset using Pandas.

Transformed the text using TfidfVectorizer to convert text to numerical features.

Used PassiveAggressiveClassifier, ideal for large-scale text classification.

Trained the model and evaluated performance.

 Accuracy Achieved:
90.4% accuracy on test data.

 Key Learnings:

Text preprocessing and vectorization using TF-IDF

Model training with Passive Aggressive Classifier

How to measure model performance in NLP tasks

Importance of fake news detection in today’s digital era
