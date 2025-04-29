# 📬 InboxIntel Overview

Spam emails can be both annoying and dangerous, often attempting to deceive individuals into revealing sensitive information or falling victim to fraud. With the increasing volume of spam circulating online, automated approaches for detecting these emails are critical for improving cybersecurity and user protection.

In this project, called **InboxIntel**, we aim to answer the following question:

> ***Can we develop a model to detect spam emails and identify keywords most indicative of spam content?***

We compiled a dataset from six major sources: CEAS, Nazario, Nigerian Fraud, and SpamAssassin corpora. In total, the dataset includes approximately 82,500 emails, with 42,891 labeled as spam and 39,595 labeled as non-spam. Each email includes the body content, subject line, sender, receiver, date sent, embedded URLs, and a spam label.


# 📂 Dataset Information

Dataset is avalible through a download link in the homepage of the website, and `data/phishing_data.csv` location in GitHub files. 

The combined and cleaned dataset is available for download below:

[**Download the Dataset (CSV)**](data/phishing_data.csv)


# 📝 Final Report

Final report is avalible through a download link in the homepage of the website, and `documents/final_report.pdf` location in GitHub files. 

A detailed project report summarizing the methodology, modeling steps, evaluation results, interpretations, and references can be accessed below:

[**Download Final Report (PDF)**](documents/final_report.pdf)


# 🧭 Website Navigation

[View Website](https://afraad.github.io/spam_email_detection/)

You can explore the full project through the following tabs:

- **EDA Tab**: Data cleaning, text normalization, summary statistics, and exploratory data visualizations.
- **Visuals Tab**: Interactive plots showing word frequency, TF-IDF scores, bigrams, timestamps, and vocabulary diversity.
- **Modeling Tab**: Model training using Naive Bayes, Logistic Regression, and MLP (Neural Network) models with hyperparameter tuning and evaluation.
- **Results Tab**: Interpretation of predictive keywords and testing the final model on example email inputs.


# 🎯 Project Objective

Using this dataset and workflow, the primary objectives of the project are:

- To train effective models that accurately classify emails as spam or non-spam.
- To identify and interpret the keywords most associated with spam email content.

This project demonstrates how machine learning and natural language processing techniques can be used to enhance email security and protect vulnerable users.

---
