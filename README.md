# Diabetes Prediction Using SVM

## Description
This project implements a **Support Vector Machine (SVM)** model to predict whether a person is diabetic or non-diabetic based on certain medical features.

### Key Features:
1. **Data Loading**: Reads a diabetes dataset using pandas.
2. **Data Exploration**: Analyzes dataset details and distribution of outcomes.
3. **Data Preprocessing**: Standardizes features and splits data for training and testing.
4. **Model Training**: Uses an SVM classifier with a linear kernel.
5. **Prediction**: Allows custom input data for predictions.

### How to Use:
1. Place your dataset (`diabetes.csv`) in the appropriate path or update the file path in the code.
2. Run the code in a Python environment (e.g., Jupyter Notebook or Colab).
3. Modify the `input_data` variable to test the model with custom data.

### Requirements:
- Python 3.6+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Dataset:
The dataset includes features like glucose levels, blood pressure, BMI, and age to predict the outcome:
- `0` → Non-diabetic
- `1` → Diabetic


