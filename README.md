# Bengaluru House Price Prediction

## Project Overview

This project predicts residential property prices in Bengaluru using Machine Learning. The dataset undergoes data cleaning, feature engineering, dimensionality reduction, and outlier removal before training and evaluating regression models.

The objective is to build an accurate house price prediction model that can estimate property prices based on features such as location, total square feet area, number of bedrooms (BHK), and bathrooms.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The project uses the Bengaluru House Price dataset containing information such as:

- Location
- Total Square Feet Area
- Number of Bedrooms (BHK)
- Bathrooms
- Price

Dataset preprocessing includes handling missing values, feature extraction, and outlier treatment.

---

## Project Workflow

### 1. Data Loading and Exploration
- Load dataset into a Pandas DataFrame
- Explore dataset structure and features

### 2. Data Cleaning
- Handle missing values
- Remove unnecessary columns
- Prepare data for analysis

### 3. Feature Engineering
- Create BHK feature
- Process total square feet values
- Extract meaningful features

### 4. Dimensionality Reduction
- Reduce location categories with very few data points
- Improve model efficiency

### 5. Outlier Removal
- Remove price-per-square-foot outliers
- Remove unrealistic BHK and bathroom combinations
- Improve data quality

### 6. Model Training
- Train Linear Regression model
- Compare with Lasso Regression and Decision Tree Regression

### 7. Model Evaluation
- Perform Cross Validation
- Use GridSearchCV for model selection

### 8. Model Export
- Export trained model using Pickle
- Export feature columns using JSON

---

## Screenshots

### Dataset Preview
![Dataset Preview](screenshots/dataset_preview.png)

### Data Cleaning
![Data Cleaning](screenshots/data_cleaning.png)

### Outlier Removal (Before)
![Outlier Removal Before](screenshots/outlier_removal_before.png)

### Outlier Removal (After)
![Outlier Removal After](screenshots/outlier_removal_after.png)

### Model Selection
![Model Selection](screenshots/model_selection.png)

### Sample Prediction
![Sample Prediction](screenshots/sample_prediction.png)

---

## Results

- Applied multiple regression algorithms for house price prediction.
- Evaluated models using Cross Validation and GridSearchCV.
- Linear Regression achieved the best performance among the tested models.
- The final model was exported for future deployment and prediction tasks.

---

## Project Structure

```
House-Price-Prediction/
│
├── House_price_prediction.ipynb
├── Bengaluru_House_Data.csv
├── bhp.csv
├── bangalore_home_prices_model.pickle
├── columns.json
├── README.md
│
└── screenshots/
    ├── dataset_preview.png
    ├── data_cleaning.png
    ├── outlier_removal_before.png
    ├── outlier_removal_after.png
    ├── model_selection.png
    └── sample_prediction.png
```

---

