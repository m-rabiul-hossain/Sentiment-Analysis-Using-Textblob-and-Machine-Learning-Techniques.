# Sentiment Analysis Based on Online Course Feedback Using Textblob and Machine Learning Techniques

# Project Overview

This project focuses on analyzing students’ sentiments toward online courses by leveraging textual feedback. Online education provides flexibility and accessibility, but understanding learners’ opinions is critical for improving course quality and engagement. The goal of this study is to develop a machine learning framework capable of classifying student feedback into positive, negative, or neutral sentiment categories, providing actionable insights for educational platforms.

# Dataset Overview

The experiments utilize the Coursera Course Reviews Dataset, which contains 107,018 student reviews and comments. The dataset includes unstructured textual feedback reflecting learners’ opinions about course content, instructors, and learning experience.


# Methodology

The methodology follows a structured pipeline:

Data Preprocessing

Text normalization (lowercasing)

Removal of punctuation and stop words

Handling missing or irrelevant entries

Feature Extraction

Vectorization of text using TF-IDF or Bag-of-Words

Polarity and subjectivity extraction with TextBlob

Model Training & Evaluation

Splitting data into training and test sets

Training multiple machine learning models

Evaluating models with metrics: Accuracy, Precision, Recall, F1-score

# Machine Learning Models

The following supervised classifiers were applied:

Logistic Regression (best performing, accuracy: 97.31%)

Support Vector Machines (SVM)

Naïve Bayes

Decision Tree

Random Forest

AdaBoost

Logistic Regression achieved the highest accuracy, outperforming other classifiers, demonstrating strong predictive capability for large-scale online course feedback analysis.

# Technologies & Tools

Programming Language: Python

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-learn

Natural Language Processing: TextBlob

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook

# Results

Logistic Regression achieved 97.31% accuracy, surpassing other classifiers.

The findings indicate that machine learning models combined with sentiment polarity extraction provide an effective approach for analyzing student feedback in online learning environments.
