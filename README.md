# Fake News Detection using Machine Learning

## Overview

This project aims to classify news articles as **Fake** or **Real** using Machine Learning models. The dataset consists of news articles with labeled authenticity, and the models are trained to automatically detect misinformation.

The implementation is done in **Python using Scikit-learn** and developed in **Google Colab**.

---

## Dataset

The dataset contains the following columns:

* **title** – News headline
* **text** – Full news article
* **label** – Indicates whether the news is *REAL* or *FAKE*

The `text` column is used as the main feature for training the models.

---

## Methodology

1. Load dataset using Pandas
2. Preprocess text data
3. Convert text to numerical vectors using **TF-IDF Vectorization**
4. Split the dataset into training and testing sets
5. Train machine learning models
6. Evaluate performance using accuracy and classification metrics

---

## Implemented Models

| Day   | Model                  |
| ----- | ---------------------- |
| Day 1 | Logistic Regression    |
| Day 2 | Naive Bayes            |
| Day 3 | Support Vector Machine |
| Day 4 | Decision Tree          |
| Day 5 | Random Forest          |
| Day 6 | K-Nearest Neighbors    |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab


## Contributors

* AkhilKrishna016
* Devsoni23
