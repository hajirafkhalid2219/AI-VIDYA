# AI-VIDYA
PROJECTS
# House Price Prediction using Machine Learning

## Overview
This repository contains a machine learning assignment that demonstrates the complete ML workflow — from a simple baseline model to a more advanced model — using a house price prediction dataset.

The objective is to understand how model complexity impacts prediction performance, interpretability, and training effort.

---

## Dataset
**Name:** Housing Price Prediction  
**Source:** Kaggle  
**Link:** https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction  

**Target Variable:**  
- `price` – Price of the house

**Features Include:**  
- Area  
- Number of bedrooms and bathrooms  
- Stories   
- Other structural attributes  (mainroad,guestroom,basement,hot water heating,basement,parking,furnishing status etc)

---

## Project 1: Baseline Model – Linear Regression

### Objective
To build a simple and interpretable prediction model and understand the fundamental machine learning pipeline.

### Steps Followed
1. Loaded the dataset using Pandas
2. Performed basic data exploration (`head()`, `info()`, `shape`)
3. Handled categorical variables by replacing with binary 0s and 1s
4. preprocessing not required
5. Split the data into training and testing sets
6. Trained a Linear Regression model using scikit-learn
7. selecting top 30 rows and columns for testing
8. Evaluate coefficients and intercepts
9. plot the actual vs predicted price
10. Evaluated performance using R² Score Mean Absolute Error (MAE) and Mean Square Error

### Outcome
- Linear Regression provided a baseline performance

## Project 2: Advanced Model – Random Forest Regressor

### Objective
To improve prediction accuracy using a more powerful ensemble learning technique and compare it with the baseline model.

### Steps Followed
1. Used the cleaned dataset from Project 1
2. Trained a Random Forest Regressor on the same training data
3. Evaluated the model using the same metrics (R² and MAE)
4. Compared results with Linear Regression

### Comparative Results
| Model | R² Score | MAE |

| Linear Regression | Baseline | Higher Error |
| Random Forest | Improved | Lower Error |

### Key Observations
- Random Forest performed better due to its ability to model non-linear relationships
- It automatically captures feature interactions
- The trade-off is increased complexity and reduced interpretability

**1. Changes observed with a stronger model:**  
The Random Forest model improved accuracy compared to Linear Regression.

**2. Most challenging part:**  
I am not able to differentiate why one model is performing better,either because linear regression does is a straight line model and the others are not
Data is small,I am also not able to figure out which one is handling outliers better
Even in the plotting ,its not a straight line

**3. Time spent on assignment:**  
Approximately 4 hours daily.

---

## Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  
- GitHub  

## Conclusion
The assignment provided a chance to learn a new modeling technique
