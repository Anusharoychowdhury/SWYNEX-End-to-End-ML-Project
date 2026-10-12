# SWYNEX-End-to-End-ML-Project
# Wine Quality Prediction Using Machine Learning

## Project Overview
This project predicts the quality score of red wine using machine learning regression models based on its physicochemical properties.

## Dataset
- **Dataset:** Red Wine Quality Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)
- **Records:** 1,599
- **Input Features:** 11
- **Target Variable:** `quality`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

## Project Workflow
1. Data loading and exploration
2. Missing-value checking
3. Data visualization and correlation analysis
4. Training and testing data split
5. Linear Regression model training
6. Random Forest Regression model training
7. Model evaluation using MAE, MSE, RMSE, and R²
8. Model comparison and selection
9. Saving and loading the selected model

## Models Used
- Linear Regression
- Random Forest Regressor

## Evaluation Metrics
- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

## How to Run
1. Download the project notebook from this repository.
2. Open it in Google Colab.
3. Upload `winequality-red.csv` when required.
4. Run the notebook cells in order.

## Model File
The selected model is saved as `best_wine_quality_model.pkl`.

## Conclusion
This project demonstrates a machine learning workflow, from data exploration and visualization to model training, evaluation, comparison, and saving the selected model.
