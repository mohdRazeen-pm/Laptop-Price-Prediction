# Laptop Price Prediction Using Machine Learning

## 1. Project Overview

This project uses machine learning to predict laptop prices
based on their technical specifications.

The system uses a Random Forest Regression model to estimate
laptop prices in euros.

## 2. Problem Statement

Laptop prices depend on several factors, including processor
specifications, RAM, storage capacity, graphics hardware,
screen size, and brand.

The objective of this project is to develop a machine learning
model that estimates laptop prices using these features.

## 3. Dataset

The dataset contains 1,275 laptop records and 15 columns.

The features include:

- Company
- Product
- Laptop type
- Screen size
- Screen resolution
- CPU manufacturer and type
- CPU frequency
- RAM
- Storage configuration
- GPU manufacturer and type
- Operating system
- Weight

Target variable: Price (Euro)

## 4. Algorithm

Random Forest Regression is used to predict laptop prices.

The model combines multiple decision trees to produce
numerical price predictions.

Categorical features are processed using One-Hot Encoding,
and numerical and categorical preprocessing is performed
using a Scikit-learn pipeline.

## 5. Model Evaluation

The model was evaluated using a separate test dataset.

Initial evaluation results:

- R² Score: 0.8757
- Mean Absolute Error (MAE): €168.14
- Root Mean Squared Error (RMSE): €248.42

These results indicate that the model explains approximately
87.57% of the variation in test-set prices relative to the
mean-price baseline.

## 6. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 7. How to Run

1. Download the repository.
2. Open the notebook in Google Colab.
3. Upload the dataset when prompted.
4. Execute the notebook cells in order.

## 8. Future Improvements

- Compare additional regression algorithms.
- Tune model hyperparameters.
- Improve feature engineering.
- Develop a Streamlit interface for price prediction.

## 9. Author

Machine Learning Assignment
