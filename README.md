# Introvert vs Extrovert Personality Classification

This repository contains my solution for the **Kaggle Playground: Predict the Introverts from the Extroverts** competition.

## 🧠 概要
行動データを基に個人の性格特性を内向型（introvert)/外向型(Extrovert)に分類することが目的です
以下が使用した特徴量の一例です:
- Time spent alone
- Stage fear
- Drained after socializing
- Social event attendance
- Friends circle size
- Online post frequency

## ⚙️ 手段
- Model: LightGBM (5-Fold Stratified CV)
- 評価指標: ROC AUC
- 主な特徴量エンジニアリング: Encoded external feature `match_p`
- 欠損値処理およびカテゴリ変数の取り扱いはPandasを使用。

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
行動データのラベル付に誤りがあることが分かり、オリジナルデータを取り入れることが精度向上の鍵となりました。
