⚽ FIFA Player Market Value Prediction

A Machine Learning project that predicts FIFA player market values using regression algorithms and an interactive Streamlit dashboard.

📌 Project Overview

Football player market value is influenced by several factors, including a player's overall rating, potential, wage, reputation, and age.

This project applies multiple Machine Learning regression techniques to estimate a player's market value based on selected player attributes. The trained models are evaluated and compared using standard regression metrics, with the results presented through an interactive Streamlit dashboard.

✨ Features
Multiple Machine Learning regression models
Hyperparameter tuning using GridSearchCV
Interactive Streamlit dashboard
Real-time player market value prediction
Model performance comparison
Data visualization and performance charts
Evaluation using MAE, RMSE, and R² Score
🤖 Models Used
Linear Regression
Decision Tree Regressor
Random Forest Regressor
XGBoost Regressor
K-Nearest Neighbors (KNN)
📊 Dataset

Dataset: players_21.csv

Features Used
Age
Overall Rating
Potential
Wage
International Reputation
Target Variable
Player Market Value (€)
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
Streamlit
Matplotlib
📈 Evaluation Metrics

The regression models are evaluated using:

MAE (Mean Absolute Error) — measures the average prediction error.
RMSE (Root Mean Squared Error) — gives greater weight to larger prediction errors.
R² Score — measures how well the model explains the variation in player market values.

💡 Key Insight

Player attributes such as overall rating, potential, wage, and age play an important role in predicting market value.

🚀 How to Run
1. Clone the Repository
git clone YOUR_GITHUB_LINK
cd YOUR_PROJECT_FOLDER

2. Install Dependencies
pip install -r requirements.txt

3. Run the Streamlit Dashboard
streamlit run app.py


The application will open in your browser, where you can enter player attributes and generate a predicted market value.

📁 Project Structure

- `app.py` — Streamlit application
- `players_21.csv` — FIFA player dataset
- `requirements.txt` — Project dependencies
- `README.md` — Project documentation

## Git Workflow

This project demonstrates collaborative development using Git branches, commits, merging, rebasing, and GitHub pull requests.

## Stash Practice

This change is temporarily saved using Git stash.

👨‍💻 Author

Prathamesh Naik

Goa University

⭐ If you found this project useful, feel free to explore the repository and give it a star!

## Cherry Pick Practice

This change will be cherry-picked to another branch.