# House Price Prediction using Machine Learning

## Xylofi AI – Week 1 Internship Project

### Project Overview

This project focuses on predicting house prices using machine learning techniques based on various property characteristics and amenities. The objective is to identify the key factors that influence housing prices and build predictive models capable of estimating property values accurately.

The project follows a complete machine learning workflow including data exploration, preprocessing, model development, evaluation, visualization, and business insight generation.

---

## Dataset Information

**Dataset:** Housing Prices Dataset

**Records:** 545

**Features:** 13

**Target Variable:** Price

### Features Included

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room Availability
* Basement Availability
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

---

## Project Workflow

### 1. Data Exploration

* Dataset inspection
* Statistical analysis
* Missing value analysis
* Duplicate record detection

### 2. Data Preprocessing

* Binary encoding for yes/no features
* One-Hot Encoding for furnishing status
* Feature preparation for machine learning

### 3. Model Development

The following regression models were evaluated:

* Linear Regression
* Random Forest Regressor
* Tuned Random Forest Regressor

### 4. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Results

| Model               |          MAE |         RMSE | R² Score |
| ------------------- | -----------: | -----------: | -------: |
| Linear Regression   |   970,043.40 | 1,324,506.96 |   0.6529 |
| Random Forest       | 1,022,560.05 | 1,401,496.84 |   0.6114 |
| Tuned Random Forest | 1,088,859.38 | 1,447,653.20 |   0.5854 |

### Best Performing Model

**Linear Regression**

R² Score: **0.6529**

The Linear Regression model achieved the best performance on unseen data and demonstrated better generalization than the Random Forest models.

---

## Key Findings

### Most Influential Features

1. Area
2. Bathrooms
3. Air Conditioning
4. Parking
5. Stories

### Business Insights

* Property area is the strongest determinant of house price.
* Houses with more bathrooms generally command higher prices.
* Amenities such as air conditioning and parking significantly contribute to property value.
* Unfurnished properties tend to have lower market prices.
* Linear relationships play a major role in this housing dataset.

---

## Visualizations

The project includes:

* House Price Distribution
* Correlation Heatmap
* Actual vs Predicted Prices
* Price vs Area Relationship
* Feature Importance Analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Repository Structure

```text
XylofiAI-House-Price-Prediction/
│
├── Housing.csv
├── analysis.ipynb
├── README.md
├── summary.pdf
│
└── charts/
    ├── house_price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    ├── price_vs_area.png
    └── feature_importance.png
```

---

## Author

**Krishnadas P S**
krishnadasps.mec@gmail.com

AI & Data Science Intern

Xylofi AI
