# 💔 Predicting Divorce Probability Using Machine Learning  

## 📌 Abstract

This project explores machine learning methods to predict divorce probability using a dataset containing a range of personal, social, and psychological variables within marriages. We aim to evaluate and compare the performance of three models:

1. A model using only the three most highly correlated features  
2. A model excluding the three least correlated features  
3. A model using all available features  

Each model will be trained and tested using standard machine learning workflows. Evaluation metrics include Mean Squared Error (MSE), R-squared, confusion matrix, accuracy score, and classification reports. We hypothesize that the model using all features will yield the most accurate predictions.

---

## 📊 Dataset Description

**Dataset Title**: Marriage and Divorce Dataset  
**Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/hosseinmousavi/marriage-and-divorce-dataset?resource=download)  
**Columns**: 31 total (30 features + 1 target)  
**Target Variable**: Divorce Probability  

**Key Feature Categories**:
- **Demographic**: Age Gap, Education  
- **Psychological**: Mental Health, Self-Confidence  
- **Compatibility**: Cultural Similarities, Common Interests, Religion Compatibility  
- **Socioeconomic**: Economic Similarity, Good Income  
- **Relational**: Love, Commitment, Communication  
- **Background**: Previous Marriage, Addiction, Family History of Divorce  

---

## ❓ Research Question

**Main Question**:  
Which machine learning model yields the most accurate prediction of divorce probability?

**Hypothesis**:  
The model trained using all features will outperform the others in predictive accuracy.

---

## ⚙️ Analytical Approach

Our approach includes:

- Feature analysis to identify the most and least correlated features  
- Model training on three different feature sets:
  - Top 3 correlated features only
  - All features except 3 least correlated
  - All features included  
- Evaluation using:
  - Mean Squared Error (MSE)
  - R-squared (R²)
  - Accuracy
- Visualizations including:
  - Pairplots for highest/lowest correlated feature models
  - Scatter plots with regression lines  
