# Author
## Name: Daryl Bubune Atito Narh <br>Index: 10211100222

# Regression Model Exploration

This project explores different regression models to predict housing prices using the California Housing dataset. The models implemented include:

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Support Vector Machine (SVM) Regressor**
- **Random Forest Regressor**

## Dataset
The dataset used is `cali-housing.csv`, which contains features related to California housing prices, including numerical and categorical variables.

## Preprocessing
The following preprocessing steps are applied:
- Handling missing values using median imputation for numerical features and most frequent imputation for categorical features.
- Standardizing numerical features using `StandardScaler`.
- Encoding categorical features using `OneHotEncoder`.
- Splitting data into training (80%) and testing (20%) sets.

## Model Training & Evaluation
Each model is trained using Scikit-learn and evaluated using:
- **Mean Squared Error (MSE)**
- **R² Score**

## Visualization
A scatter plot is generated comparing actual vs. predicted values for all models.

## Dependencies
The following Python libraries were used:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
