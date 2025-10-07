# Introvert vs Extrovert Personality Classification

This repository contains my solution for the **Kaggle Playground: Predict the Introverts from the Extroverts** competition.

## 🧠 Overview
The goal is to classify a person as an Introvert or Extrovert based on behavioral features such as:
- Time spent alone
- Stage fear
- Drained after socializing
- Social event attendance
- Friends circle size
- Online post frequency
- ...and more.

## ⚙️ Methods
- Model: LightGBM (5-Fold Stratified CV)
- Evaluation Metric: ROC AUC
- Key Feature Engineering: Encoded external feature `match_p`
- Handling missing values and categorical encoding with Pandas.

## 📈 Results
- OOF AUC: **0.9725**
- Final Public Leaderboard: **Top 102 / 4447 participants**

## 📂 Files
- `play last.ipynb` : Main notebook
- `submission.csv` : Example submission file

## 🧰 Tools
- Python 3.10
- Pandas, LightGBM, NumPy, Scikit-learn

## 🏅 Notes
This work is part of my ongoing machine learning portfolio.
