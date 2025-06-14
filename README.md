# Regression

## Overview  
This project demonstrates the implementation of **Simple, Multiple, and Polynomial Linear Regression**, along with **Logistic Regression**, to solve real-world problems using datasets such as `50_Startups.csv`, `Position_Salaries.csv`, and a university admissions dataset.  



## Objectives  
### Part A: Linear Regression  
- Apply **Simple and Multiple Linear Regression** on the `50_Startups.csv` dataset.  
- Apply **Polynomial Linear Regression** on the `Position_Salaries.csv` dataset.  
- Visualize the training and testing set results.  

### Part B: Logistic Regression  
- Build a **Logistic Regression Model** to predict university admissions based on GRE score, GPA, and institution prestige.  
- Perform the following steps:  
  - Data Preprocessing  
  - Model Development  
  - Prediction  
  - Evaluation  
  - Interpretation  



## Part A: Linear Regression  

### Datasets  
- **50_Startups.csv**: Used for Simple and Multiple Linear Regression.  
- **Position_Salaries.csv**: Used for Polynomial Linear Regression.  

### Steps Performed  
1. **Data Preprocessing**:  
   - Handled missing values, if any.  
   - Encoded categorical variables using `LabelEncoder` and `OneHotEncoder`.  

2. **Simple and Multiple Linear Regression**:  
   - Built regression models using `LinearRegression` from `sklearn.linear_model`.  
   - Evaluated and visualized results on both the training and testing sets.  

3. **Polynomial Regression**:  
   - Used `PolynomialFeatures` from `sklearn.preprocessing` to create polynomial features.  
   - Built and evaluated models for higher-order polynomials.  

4. **Visualization**:  
   - Plotted regression lines and data points for both training and testing sets to compare model performance.  



## Part B: Logistic Regression  

### Dataset  
A dataset containing the following features:  
- **GRE Score**: Standardized test score for graduate admissions (out of 340).  
- **GPA**: Grade Point Average (on a scale of 0 to 4).  
- **Prestige**: Prestige of the undergraduate institution (1 = Most Prestigious, 4 = Least Prestigious).  
- **Admission Status**: Binary variable indicating admission (1) or rejection (0).  

### Steps Performed  
1. **Data Preprocessing**:  
   - Normalized numerical data.  
   - Encoded categorical variables (if applicable).  

2. **Model Development**:  
   - Built a Logistic Regression model using `LogisticRegression` from `sklearn.linear_model`.  

3. **Prediction**:  
   - Predicted admission status for new applicants.  

4. **Evaluation**:  
   - Evaluated the model using metrics like accuracy, precision, recall, F1 score, and confusion matrix.  

5. **Interpretation**:  
   - Analyzed the impact of GRE scores, GPA, and Prestige on admission likelihood.  


## Files Included  

| File Name                   | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `50_Startups.csv`           | Dataset for Simple and Multiple Linear Regression.                         |
| `Position_Salaries.csv`     | Dataset for Polynomial Linear Regression.                                  |
| `simple_linear_regression.ipynb` | Notebook for Simple Linear Regression analysis.                        |
| `logistic_regression.ipynb` | Notebook for Logistic Regression analysis.                                 |
| `Salary_Data.csv`           | Supporting dataset for regression practice.                                |
| `Heart.csv`                 | Additional dataset for testing models (optional).                          |

---

