# Heart Disease Prediction Project

This project utilizes machine learning techniques to predict the presence of heart disease based on clinical and demographic data.

## Key Features

- **Data Cleaning and Preprocessing**: The dataset (`processed_cleveland.csv`) is cleaned by handling missing values and outliers.
  
- **Outlier Detection**: Outliers in the target variable (`num`) are identified and removed using the Interquartile Range (IQR) method.

- **Feature Selection**: Harris Hawk Optimization (HHO) algorithm is employed to select the most relevant features for predicting heart disease.

- **Model Training**: A Random Forest Classifier is trained on the selected features to build the predictive model.

- **Model Evaluation**: Accuracy metrics are calculated to evaluate the performance of the trained model.

- **README**: A README file (`README.md`) is included to provide detailed instructions on installation, usage, and credits for the project.

## Installation

Ensure you have Python 3.x installed. Install necessary dependencies using pip:

```bash
pip install numpy matplotlib pandas scikit-learn zoofs
