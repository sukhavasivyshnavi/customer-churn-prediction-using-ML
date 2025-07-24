# Customer Churn Prediction using Machine Learning

This project aims to build a predictive model that determines whether a telecom customer is likely to churn, based on their service usage patterns and demographic information.

## Objective

To analyze customer behavior and build a machine learning model that predicts churn, helping businesses reduce customer loss and improve retention strategies.

## Dataset

- **Source**: [Telco Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size**: 7043 rows × 21 columns
- **Target Column**: `Churn` (Yes/No)

## Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Steps

1. **Data Cleaning**
   - Removed irrelevant columns (e.g., customerID)
   - Handled missing values in `TotalCharges`
   - Converted data types as needed

2. **Data Preprocessing**
   - Encoded categorical variables using Label Encoding
   - Normalized and structured the dataset

3. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution
   - Analyzed feature correlations

4. **Model Building**
   - Split data into training and test sets
   - Trained a Random Forest Classifier
   - Evaluated model using accuracy score, confusion matrix, and classification report

5. **Model Performance**
   - Achieved approximately 80–85% accuracy
   - Identified key features impacting churn: Contract Type, Tenure, MonthlyCharges, and InternetService

## Results

The model successfully predicts customer churn with high accuracy, allowing businesses to proactively identify customers at risk of leaving and take appropriate retention actions.

## How to Run

1. Clone this repository
2. Install required packages:

## Author

S. Vyshnavi  
Email:sukhavasivyshnavi17@gmail.com
