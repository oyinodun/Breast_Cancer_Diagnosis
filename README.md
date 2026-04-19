# Breast Cancer Classification using Machine Learning

## Overview
This project analyzes tumor characteristics and builds a machine learning model to classify breast cancer cases 
as benign or malignant.

## Dataset
- Source: Kaggle (Erdemtaha Cancer Dataset) : https://www.kaggle.com/datasets/erdemtaha/cancer-data
- ~570 samples
- 30 numerical features
- Target: Diagnosis (M = Malignant, B = Benign)

## Steps taken to build the Project

### 1. Data Preprocessing
- Removed irrelevant columns (id, empty fields)
- Encoded target variable (M as 1 and B as 0)
- Did a Train-test split (80/20)
- Feature scaling using StandardScaler

### 2. Exploratory Data Analysis
- Histograms to understand feature distributions
- Boxplots to analyze class separation

### 3. Modeling
- Logistic Regression was used as the primary model
- Evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC-AUC Curve

### 4. Results
- Accuracy: 97%
- Strong performance across both classes
- High recall for malignant cases (95%)

### 5. Key Insights
- Tumor size features (radius, area, perimeter) are strong predictors

### 6. Future Improvements
- Try analysis with Random Forest
- Apply L1 regularization for feature selection
- Use SMOTE to address class imbalance

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn / Matplotlib

## How to Run
1. Clone the repository
2. Install dependencies
3. Run the notebook attached to this repository.
