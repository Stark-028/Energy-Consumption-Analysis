# Energy Consumption Analysis and Prediction

## Project Overview
This project aims to analyze and predict the heating and cooling load requirements of buildings using various regression models. The dataset includes 768 instances with features like `Relative Compactness`, `Surface Area`, `Wall Area`, `Roof Area`, `Overall Height`, `Orientation`, `Glazing Area`, and `Glazing Area Distribution`.

## Dataset
The dataset used in this project consists of 8 features and 2 target variables:
- **Features**:
  - `Relative Compactness`
  - `Surface Area`
  - `Wall Area`
  - `Roof Area`
  - `Overall Height`
  - `Orientation`
  - `Glazing Area`
  - `Glazing Area Distribution`
- **Target Variables**:
  - `Heating Load`
  - `Cooling Load`

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation heatmap
   - Pairplots

2. **Data Preprocessing**
   - Handling missing values
   - Scaling features
   - Polynomial feature transformation
   - Dimensionality reduction using PCA

3. **Modeling**
   - Linear Regression
   - Ridge Regression
   - Lasso Regression

4. **Hyperparameter Tuning**
   - GridSearchCV for optimizing Ridge Regression

5. **Model Evaluation**
   - Mean Squared Error (MSE)
   - Mean Absolute Error (MAE)
   - R² Score
   - Explained Variance Score (EVS)
   - Cross-validation

6. **Residual Analysis**
   - Residuals distribution
   - Residuals vs. fitted values

7. **Learning Curves**
   - Diagnose model performance using learning curves

## Results
The optimized Ridge Regression model provided the best performance with the following metrics:
- Mean Squared Error (MSE): [value]
- Mean Absolute Error (MAE): [value]
- R² Score: [value]
- Explained Variance Score (EVS): [value]

## Visualizations
Key visualizations from the analysis:
- Correlation heatmap
- Pairplots
- Actual vs. Predicted values
- Residuals distribution
- Learning curves
