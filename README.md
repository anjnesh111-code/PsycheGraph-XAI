# PsycheGraph-XAI

## Explainable Depression Risk Prediction using SHAP-Grounded Large Language Model Explanations and Evidence-Based Recommendations

PsycheGraph-XAI is an Explainable Artificial Intelligence (XAI) framework designed to predict depression risk among students while providing understandable explanations and wellness-oriented recommendations.

The framework combines machine learning prediction, SHAP explainability, Gemini-generated natural language explanations, and evidence-based recommendations to improve the interpretability of depression risk assessment.

---

## Overview

Mental health challenges among students continue to grow due to factors such as academic pressure, financial stress, lifestyle imbalance, and psychological burden. While machine learning models can assist in identifying individuals at risk, many existing systems provide limited transparency regarding how predictions are made.

This project was developed to address this challenge by integrating:

- Machine Learning-based Depression Risk Prediction
- SHAP Explainability
- Gemini-powered Human-Readable Explanations
- Evidence-Based Recommendation Generation

The objective is to provide accurate predictions while making the reasoning behind those predictions easier to understand.

---

## Key Features

- Depression Risk Prediction using Machine Learning
- Logistic Regression, Random Forest, and XGBoost Models
- SHAP-based Explainability
- Gemini-generated Natural Language Explanations
- Personalized Evidence-Based Recommendations
- Interactive Streamlit Dashboard
- Human-Centered Explainable AI Framework

---

## Dataset

This project uses the publicly available Student Depression Dataset from Kaggle.

Dataset Features Include:

- Academic Pressure
- Financial Stress
- Work/Study Hours
- Sleep Duration
- Dietary Habits
- Study Satisfaction
- Suicidal Thoughts
- Family History of Mental Illness
- Depression Status

Dataset Size:

- Approximately 27,900 student records

Dataset Source:
https://www.kaggle.com/datasets/hopesb/student-depression-dataset

---

## Methodology

### 1. Data Preprocessing

- Data Cleaning
- Missing Value Handling
- Feature Encoding
- Feature Scaling

### 2. Machine Learning Models

The following models were evaluated:

- Logistic Regression
- Random Forest
- XGBoost

### 3. Explainability Layer

SHAP (SHapley Additive exPlanations) was used to:

- Identify important behavioral factors
- Generate local explanations
- Generate global explanations

### 4. Natural Language Explanation Generation

Gemini API was integrated to convert SHAP feature contributions into human-readable explanations.

### 5. Recommendation Layer

Recommendations are generated using:

- SHAP Important Features
- Trusted Mental Health Resources
- Wellness-Oriented Guidance

---

## System Architecture

```text
Student Data
      │
      ▼
Data Preprocessing
      │
      ▼
Machine Learning Model
(Logistic Regression / RF / XGBoost)
      │
      ▼
SHAP Explainability
      │
      ▼
Gemini Explanation Generation
      │
      ▼
Evidence-Based Recommendation Layer
      │
      ▼
User-Friendly Output
```

---

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 84.55% |
| XGBoost | 84.03% |
| Random Forest | 83.82% |

Key Factors Associated with Depression Risk:

- Suicidal Thoughts
- Academic Pressure
- Financial Stress
- Work/Study Hours

Protective Factors:

- Healthy Sleep Duration
- Higher Study Satisfaction

---

## Example Output

### Prediction

```
Depression Risk: High
```

### Explanation

```
The prediction was influenced mainly by high academic pressure,
financial stress, and reduced sleep duration.
```

### Recommendation

```
Consider improving sleep habits, managing workload,
and seeking professional support if required.
```

---

## Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-learn
- XGBoost

### Explainable AI

- SHAP

### Data Processing

- Pandas
- NumPy

### Visualization

- Matplotlib

### LLM Integration

- Gemini API

### Deployment

- Streamlit

### Development Environment

- Kaggle Notebook
- Google Colab

---

## Project Structure

```text
PsycheGraph-XAI/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── notebooks/
│   └── training_notebook.ipynb
├── figures/
│   ├── architecture.png
│   ├── shap_summary.png
│   └── dashboard.png

```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/PsycheGraph-XAI.git
```

Move into the project directory:

```bash
cd PsycheGraph-XAI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app/streamlit_app.py
```

---

## Research Contribution

This project contributes:

- Explainable Depression Risk Prediction
- Integration of SHAP and Gemini
- Human-Readable Mental Health Explanations
- Evidence-Based Recommendation Generation
- A Human-Centered Explainable AI Framework

---

## Publication Status

Research Paper:

**PsycheGraph-XAI: Explainable Depression Risk Prediction with SHAP-Grounded LLM Explanations and Evidence-Based Personalized Recommendations**

Status:

- Submitted for Publication

---

## Future Work

Possible future directions include:

- Clinical Validation
- Multimodal Mental Health Data
- Advanced Deep Learning Models
- Improved Recommendation Systems
- Real-World Deployment Studies

---

## Disclaimer

This project is intended for research and educational purposes only.

The predictions, explanations, and recommendations generated by the system should not be considered medical advice, psychiatric diagnosis, or professional healthcare recommendations.

Users should consult qualified healthcare professionals for mental health assessment and treatment.

---

## Author

**Anjnesh Singh Tomar**

B.Tech Artificial Intelligence and Data Science

Chameli Devi Group of Institutions, Indore

GitHub: https://github.com/anjnesh111-code

LinkedIn: https://www.linkedin.com/in/anjnesh-singh-tomar/

---
