Solubility Prediction using Machine Learning

📌 Project Overview

This project demonstrates a simple machine learning workflow to predict the aqueous solubility of chemical compounds (logS values) based on molecular descriptors.


📂 Dataset

Source: Delaney Solubility Dataset

Target Variable: logS (aqueous solubility)

Features: Molecular descriptors (various numerical columns)

⚙️ Steps in the Notebook

Load Dataset using pandas.

Exploratory Data Analysis (EDA) to understand data distribution.

Feature & Target Separation:

X → Molecular descriptors

y → Solubility (logS)

Model Building (Regression models like Linear Regression, Random Forest, etc.)

Model Evaluation using metrics such as RMSE, R² score.

🛠️ Tech Stack

Python

Pandas, NumPy (Data Handling)

Scikit-learn (Model Training & Evaluation)

Matplotlib / Seaborn (Visualization)

📈 Results

The trained regression model is able to predict solubility values with reasonable accuracy.

Metrics (RMSE, R²) show how well the model generalizes on unseen data.
