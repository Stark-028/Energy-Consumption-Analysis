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
- PCA explained variance
- Actual vs. Predicted values
- Residuals distribution
- Learning curves

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/Energy-Consumption-Analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Energy-Consumption-Analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebook:
    ```bash
    jupyter notebook Energy_Consumption_Analysis.ipynb
    ```

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any improvements or suggestions.

## License
This project is licensed under the MIT License.

## Contact
For any questions or inquiries, please contact [Your Name](mailto:your.email@example.com).

---

### Upload the Project to GitHub
1. **Push the code**:
   - Open a terminal.
   - Navigate to your project directory.
   - Initialize a git repository and add your remote:
     ```bash
     git init
     git remote add origin https://github.com/your_username/Energy-Consumption-Analysis.git
     ```
   - Add your files and commit:
     ```bash
     git add .
     git commit -m "Initial commit"
     ```
   - Push to GitHub:
     ```bash
     git push -u origin master
     ```

2. **Upload the HTML version of the notebook**:
   - Convert your notebook to HTML:
     ```bash
     jupyter nbconvert --to html Energy_Consumption_Analysis.ipynb
     ```
   - Add the HTML file to your repository:
     ```bash
     git add Energy_Consumption_Analysis.html
     git commit -m "Add HTML version of the notebook"
     git push
     ```

By following these steps, you'll have a well-documented GitHub repository showcasing your Energy Consumption Analysis and Prediction project. This will make it easy for others to understand, reproduce, and appreciate your work.
