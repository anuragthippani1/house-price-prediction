House Price Prediction

📋 Project Overview

This project aims to predict house prices using a dataset containing features like geographical location, housing characteristics, and socio-economic indicators. The models implemented include Linear Regression and Random Forest Regressor.

The dataset used is housing.csv, which contains real-world data on housing prices and related features. The project demonstrates data preprocessing, feature engineering, model training, and evaluation.


🧑‍💻 Features

Predicts median_house_value based on:
Geographic details (longitude, latitude)
Housing characteristics (age, number of rooms, bedrooms, etc.)
Population and household statistics
Median income in the area
Implements machine learning models:
Linear Regression for baseline predictions
Random Forest Regressor for improved accuracy with hyperparameter tuning
Visualizations to understand data relationships and insights.

📂 Dataset

The dataset housing.csv contains:

9 Columns:
longitude, latitude: Geographical coordinates
housing_median_age: Age of housing in the area
total_rooms, total_bedrooms: Housing details
population, households: Area demographics
median_income: Scaled income
median_house_value: Target variable for predictions
20,640 Entries


🛠️ Methodology

Data Preprocessing:
Handle missing values in total_bedrooms.
Apply transformations like log scaling for skewed features.
Exploratory Data Analysis (EDA):
Visualize correlations and trends.
Create new features (e.g., bedroom-to-room ratio).
Model Training:
Train Linear Regression and Random Forest Regressor models.
Optimize Random Forest with GridSearchCV.
Model Evaluation:
Metrics like RMSE, MAE, and R² are used to assess performance.


🚀 How to Run

Clone the repository:
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook houseprice_prediction.ipynb

📊 Results

Linear Regression: Baseline model with moderate accuracy.
Random Forest Regressor: Improved predictions with optimized hyperparameters.
Achieved a low RMSE and high R² score, demonstrating the model's effectiveness.

🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any feature additions or improvements.


📝 License

This project is licensed under the MIT License.
