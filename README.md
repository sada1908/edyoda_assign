# edyoda_assign
Edyoda Assignments Python &amp; Agentic AI
📌 Problem Statement
Given a dataset of residential house listings, the objective is to build a regression model that can accurately predict the price of a house based on its features. This project demonstrates data preprocessing, visualization, and tuning of the KNN model to optimize performance.

📂 Dataset
The dataset was sourced from Edyoda’s GitHub repository.
Although the original dataset referred to rental values, this implementation repurposes it for price prediction modeling.

🧮 Features Used

Size (in square feet)
BHK (number of bedrooms)
Bathroom count
Floor level
Total number of floors

🛠️ Technologies & Tools
Python (Pandas, NumPy, Scikit-learn)
Data Visualization: Matplotlib, Seaborn
Model: KNeighborsRegressor
Jupyter Notebook

🔍 Key Steps
Data Exploration: Checked data types, null values, and feature distribution
Visualization: Plotted rent distribution, BHK vs Rent, Furnishing vs Rent, and Correlation Heatmap
Preprocessing: One-hot encoding for categorical variables, feature selection
Model Training: Applied KNN Regressor and evaluated using Mean Squared Error (MSE)
Hyperparameter Tuning: Identified optimal value of k based on performance
