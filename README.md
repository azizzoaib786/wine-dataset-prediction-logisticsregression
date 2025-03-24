# Wine Class Prediction using Logistic Regression and Feature Engineering (Lasso Regularization)

## Overview
This project uses Logistic Regression combined with feature engineering through Lasso regularization to predict the class of wine. The dataset comprises both seen and unseen data, where the model is trained on seen data and evaluated on unseen data to determine predictive performance.

## Project Goals
- Predict wine class using Logistic Regression.
- Implement feature engineering using Lasso regularization to select significant predictors.
- Understand and address overfitting through model adjustments and feature selection.
- Provide insights into bias-variance trade-off based on model performance.

## Steps Included

### 1. Data Preparation
- Cleaning and structuring the dataset for analysis

### 2. Data Visualization
- Plotting data to identify trends and initial insights

### 3. Data Splitting
- Splitting dataset into training and testing subsets

### 4. Initial Model Training
- Applying Logistic Regression model on training data without feature engineering (resulting in overfitting)

### 5. Feature Engineering
- Using Lasso Regularization to identify and extract important features for improved prediction

### 6. Model Retraining
- Training Logistic Regression model again using the selected features to address overfitting and enhance performance

### 7. Bias-Variance Analysis
- Providing insights and justifications on the bias-variance trade-off based on model evaluation results

### 8. Final Predictions
- Applying the optimized Logistic Regression model on unseen data to predict wine classes

## How to Run
To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/azizzoaib786/wine-dataset-prediction-logisticsregression.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open `wine-dataset-prediction-logisticsregression.ipynb` in Jupyter Notebook or JupyterLab.
   - Execute all cells (`Run All`).

## Requirements
- Python (3.7 or higher recommended)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook/JupyterLab

## Contributions
Contributions are encouraged! Fork the repository, make improvements, and submit a pull request.

## Contact
- Email: [azizzoaib786@gmail.com](mailto:azizzoaib786@gmail.com)

## License
This project is licensed under the MIT License.