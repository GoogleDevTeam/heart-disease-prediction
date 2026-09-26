# AI Bootcamp Machine Learning Project

This repository contains machine learning projects and educational materials developed as part of an AI Bootcamp. It covers a variety of machine learning concepts, models, and datasets.

## Project Structure

*   **`ML.ipynb`**: Demonstrates various machine learning regression models (Linear Regression, Decision Tree, Random Forest, XGBoost, etc.) and compares their performance using metrics like MAE, RMSE, and R-Squared.
*   **`DNN_Breast_Cancer_Educational.ipynb`**: An educational notebook that explores Deep Neural Networks (DNN) applied to breast cancer classification, comparing Scikit-learn's `MLPClassifier` with a custom TensorFlow/Keras neural network.
*   **`(Starter).ipynb`**: Contains starter code and initial exploratory data analysis templates.
*   **`Testman/Heart_Disease_Prediction.ipynb`**: Focuses on classifying heart disease using Logistic Regression and Random Forest classifiers, including feature importance analysis and ROC curve visualization.

## Datasets

*   `data.csv`: Main dataset used for regression modeling in `ML.ipynb`.
*   `Salary_Data.csv`: Salary dataset for simple regression tasks.
*   `Testman/heart.csv`: Heart disease dataset containing patient metrics.

## Setup Instructions

1. Clone the repository.
2. Ensure you have Python installed along with the following libraries:
   * `pandas`
   * `numpy`
   * `scikit-learn`
   * `matplotlib`
   * `seaborn`
   * `xgboost`
   * `tensorflow` (for the DNN notebook)
3. Open the `.ipynb` notebooks using Jupyter Notebook or JupyterLab.
4. Run the cells in order to train the models and visualize the results.

## Model Saving

The notebooks demonstrate how to save and load trained models using `joblib` and `h5` formats. The code handles creating a `saved_models` directory to organize output artifacts.
