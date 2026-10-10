
---
title: AI-Based Customer Complaint Risk Detection
permalink: /projects/food-delivery-risk/
---

[Home]({{ '/' | relative_url }}) | [All Projects]({{ '/projects/' | relative_url }})

# AI-Based Customer Complaint Risk Detection

## Project Overview

This project explores how deep learning and big data
analytics concepts can be applied to customer complaints
from online food delivery platforms.

The objective is to classify complaint-related feedback
and assess potential risk severity, helping managers
identify issues that may require further investigation.

## Problem Statement

Customer reviews contain useful information about delivery
problems, food quality, payment issues, and service
experiences. Manually reviewing large volumes of feedback
can make it difficult to identify recurring concerns.

This project investigates an analytical approach to
organizing feedback and highlighting potentially important
complaints.

## Objectives

1. Prepare and analyse customer review data.
2. Develop an LSTM model for complaint classification.
3. Categorize feedback into meaningful issue types.
4. Develop a risk scoring approach for prioritization.
5. Present findings through an interactive dashboard.

## Tools and Technologies

- Python
- Pandas and NumPy
- TensorFlow / Keras
- Natural Language Processing
- Streamlit
- Matplotlib / Seaborn, if used

## Methodology

### 1. Data Preparation

Cleaned the review text, handled missing values and
duplicates, and prepared the data for analysis.

### 2. Exploratory Data Analysis

Examined review distributions, complaint patterns,
ratings, and sentiment.

### 3. Model Development

Developed an LSTM-based text classification model
to predict complaint-related labels.

### 4. Risk Analysis

Combined selected indicators into a risk scoring
framework to prioritize feedback for further review.

### 5. Dashboard Development

Built a Streamlit dashboard to explore review data,
complaint categories, model predictions, and risk levels.

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

- Source Code: [Add GitHub repository URL]
- Live Demo: [Add Streamlit URL, if available]
- Dataset: [Add a public dataset reference, if permitted]
