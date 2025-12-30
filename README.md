# Car-Price-Prediction
# 🚗 Car Selling Price Prediction (Machine Learning)
This project applies machine learning regression techniques to predict the selling price of used cars based on their attributes. The workflow includes data cleaning, outlier handling, feature engineering, normalization, model training using Linear Regression, evaluation, and final prediction on a new unseen data point.
# 📂 Dataset
The dataset is sourced from Kaggle and is not included in this repository due to licensing restrictions. You can download it here: https://www.kaggle.com/datasets/mahnazarjmand/cardata After downloading, place the file in: Data/cardata.csv The notebook loads the dataset from this location.
# 📊 Project Workflow
The notebook begins with exploratory data analysis to understand the dataset, identify noise, and detect outliers. Visualizations such as boxplots, pairplots, and correlation heatmaps help reveal patterns and guide preprocessing decisions. All generated figures are saved in the images folder to keep the notebook clean and organized. Outliers are removed to improve model stability. Feature engineering includes log transformations and an interaction feature to reduce skewness and capture more meaningful relationships. Selected numerical features are normalized to ensure consistent scaling. The core machine learning model used in this project is Linear Regression, implemented through standard Python ML libraries. The model is trained, evaluated using metrics such as MAE, MSE, RMSE, and R², and tested under different configurations to avoid overfitting. Once the best setup is identified, the model predicts the selling price for a new car based on its attributes.
# ▶️ How to Run the Project
•	Download the dataset from Kaggle and place it in the Data folder.
•	Open the notebook Car Price Prediction.ipynb.
•	Run the cells in order. The notebook performs all steps automatically: data preparation, feature engineering, scaling, model training, evaluation, and final prediction. No additional setup is required beyond standard Python data science libraries.
