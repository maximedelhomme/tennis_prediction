# Tennis Match Outcome Prediction

A personal project designed to predict the outcome of tennis matches based on historical and performance-related player statistics.

## Goal

Predict the winner of a tennis match using a logistic regression model trained on handcrafted features derived from player Elo rating, recent form, and match history.

## Stack

- Python (Pandas, NumPy, scikit-learn)
- Feature engineering (Elo rating difference, winrate by surface, head-to-head wins, etc.)
- Modeling: Logistic Regression
- Model evaluation (accuracy, train/test split, class balancing)

## Outcome

- A binary classification model with an accuracy score of ~69%
- Custom features created by combining raw variables:
  - `elo_diff`
  - `h2h_diff`
  - `form5_diff`
  - `surface_winrate_diff`
  - `winrate_diff`
- Clean and well-documented notebook including preprocessing and model training

## 📁 Repository Structure

tennis-prediction/
│
├── tennis_prediction.ipynb
├── data/
│ └── Tennis_sample.csv 
├── README.md 
