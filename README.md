# 🧠 Stroke Prediction App

> An AI-powered web application for estimating stroke risk from selected health and demographic factors.

## 📌 Overview

**Stroke Prediction App** is a machine-learning-based web application designed to demonstrate how selected demographic and health-related factors can be used to estimate an individual's predicted stroke risk.

The application provides an interactive interface where users can enter:

- Age
- Gender
- Height and weight
- Average glucose level
- Hypertension status
- Heart disease status
- Marital status
- Work type
- Residence type
- Smoking status

The application then processes the input through a trained machine-learning pipeline and returns an estimated stroke-risk probability.

> ⚠️ **Important:** This application is an educational/research prototype and is **not a medical diagnostic tool**. Predictions should not be used as a substitute for professional medical advice.

---

## ✨ Features

### 🧑‍⚕️ Health & Demographic Input

Users can provide information related to:

- Personal demographics
- BMI
- Blood glucose level
- Hypertension
- Heart disease
- Smoking status
- Lifestyle-related factors

### 🤖 Machine Learning Prediction

The application loads a pre-trained machine-learning pipeline and generates a probability estimate for stroke risk.

### 📊 Risk Visualization

The predicted probability is displayed using an interactive gauge chart with different risk ranges.

### 💡 Personalized Recommendations

Based on selected risk factors, the application provides general lifestyle and screening recommendations.

---

## 🏗️ Application Workflow

```text
User Input
    │
    ▼
Data Validation
    │
    ▼
Feature Processing
    │
    ▼
Pre-trained ML Pipeline
    │
    ▼
Stroke Risk Probability
    │
    ├──► Risk Visualization
    │
    └──► General Recommendations
