
# 📱 SMS Spam Detection using Machine Learning

## 📌 Project Overview

SMS Spam Detection is a machine learning project that classifies SMS messages as either **Spam** or **Not Spam**. The system uses Natural Language Processing (NLP) techniques to convert text messages into numerical features and a Multinomial Naive Bayes classifier to perform the classification.

The project provides an interactive Streamlit interface where users can enter an SMS message and receive a prediction.

## 🎯 Objectives

- Detect unwanted and potentially fraudulent SMS messages.
- Apply NLP techniques to text data.
- Convert SMS text into numerical features using TF-IDF.
- Train a machine learning classification model.
- Evaluate the model using standard performance metrics.
- Provide an easy-to-use interface for SMS prediction.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Multinomial Naive Bayes
- Streamlit
- Matplotlib
- Seaborn
- Joblib

## 📊 Dataset

The project uses the **SMS Spam Collection dataset**, containing 5,572 SMS messages labelled as either:

- **Ham** – normal SMS messages
- **Spam** – unwanted SMS messages

## 🔄 Methodology

```text
SMS Dataset
     ↓
Data Preprocessing
     ↓
Train-Test Split
     ↓
TF-IDF Feature Extraction
     ↓
Multinomial Naive Bayes
     ↓
Model Evaluation
     ↓
Spam / Not Spam Prediction
## 📸 Prediction Example

The application classifies SMS messages as Spam or Not Spam.

![SMS Spam Prediction](sms-prediction.png)
