
 # 🏏 IPL Win Predictor

This project is an **IPL (Indian Premier League) Win Predictor** built using machine learning. It predicts the win probability of the batting and bowling teams during a match using match context like current score, overs completed, and wickets lost.


## 🚀 Live Demo

Check out the live Streamlit app here: [IPL Win Predictor](https://ipl-win-predictor-sahasranshu.streamlit.app/)

---

## 📊 Features

- Predicts live match win probabilities.
- User selects:
  - Batting team
  - Bowling team
  - Host city
  - Target score
  - Current score
  - Overs completed
  - Wickets fallen
- Outputs real-time win percentages for both teams.

---

## 📁 Dataset

- Source: [Kaggle IPL Dataset]([https://www.kaggle.com/](https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set?select=deliveries.csv))
- Preprocessed to include only relevant match situations and eliminate noise (e.g., rain-affected matches, incomplete games).
- Created features like `runs_left`, `balls_left`, `wickets_left`, `current_run_rate`, and `required_run_rate`.

---

## 🧠 Model

- **Model used:** Logistic Regression (sklearn)
- Trained on engineered features to predict the probability of a team winning based on current match context.
- Achieved satisfactory accuracy and generalization on test data.

---

## 🛠 Tech Stack

- **Python**
- **Pandas & NumPy** – Data preprocessing
- **Scikit-learn** – Model training
- **Streamlit** – Web app deployment


---



