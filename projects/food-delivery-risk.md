
---
title: AI-Based Customer Complaint Risk Detection
permalink: /projects/food-delivery-risk/
---

[Home](README.md) | [All Projects](projects.md)

# An AI-Driven Big Data and Deep Learning Framework for Complaint Detection and Risk Severity Assessment on Online Food Delivert Platforms 

<p align="center">
  <img src="food.png" width="800">
</p>

## Project Overview

This project explores how deep learning, big data and cloud computing and risk analysis concepts can be applied to customer complaints on online food delivery platforms.

The objective is to classify complaint-related feedback and assess potential risk severity, helping managers to identify issues that may require further investigation.

## Problem Statement

Customer reviews contain useful information for food delivery platforms such as delivery problems, food quality, order accuracy, restaurant issues, payment and refund issues, pricing issues, application and technical problems and service experiences. Manually reviewing large volumes of feedback can make it difficult to identify recurring concerns. 

This project investigates an analytical approach to organizing feedback and highlighting potentially important complaints.

## Objectives

1. To develop and compare LSTM and GRU deep learning models in detecting and classifying complaint comments from food delivery platform reviews.
2. To build a structured cloud-based big data pipeline for ingestion, processing, storage, and analysis for a large-scale customer review data to support decision-making in transforming raw user-generated contents into a reliable and high-quality data.
3. To assess risk severity level using a probabilistic risk scoring model based on sentiment polarity, customer ratings, complaint categories and frequencies.

## Tools and Technologies

- Python
- Pandas and NumPy
- TensorFlow / Keras
- Natural Language Processing
- Matplotlib / Seaborn
- Streamlit

## Methodology

### 1. Data Preparation

Cleaned the review text, handled missing values and duplicates, and prepared the data for analysis.

### 2. Exploratory Data Analysis

Examined review distributions, complaint patterns, ratings, and sentiment.

### 3. Model Development

Developed an LSTM-based text classification model to predict complaint-related labels.

### 4. Risk Analysis

Combined selected indicators into a risk scoring framework to prioritize feedback for further review.

### 5. Dashboard Development

Built a Streamlit dashboard to explore review data, complaint categories, model predictions, and risk levels.

## Model Evaluation

Report the metrics measured on your held-out test set.

- Accuracy: 87%
- ROC-AUC: 0.938

Include precision, recall, F1-score, and a confusion
matrix where appropriate. Explain which errors matter
most for this application.

## Key Findings

Add three to five findings supported by your actual
analysis, such as recurring complaint categories,
differences between platforms, or patterns in risk levels.

Do not include claims that have not been verified
against your results.

## Challenges and Lessons Learned

Describe challenges in text preprocessing, model
training, classification errors, or dashboard integration.

Explain how you addressed them and what you would
improve in a future version.

## Project Links

- Dataset: [Food Delivery Apps Reviews on Kaggle](https://www.kaggle.com/datasets/skamlo/food-delivery-apps-reviews)
- GitHub Source Code: [GitHub Repository](https://github.com/XINnn2/FOOD)
- Live App Demo: [Food Delivery Complaints Apps](https://complaint-system.streamlit.app/)
- Finding Report: [Report](https://canva.link/78hec0napcbogm4)
