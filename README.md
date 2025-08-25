# Salary Dataset Analysis

This project demonstrates a simple linear regression analysis on a salary dataset using Python and Jupyter Notebook. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, and building a regression model to predict salary based on years of experience.

## Dataset
- **File:** `Dataset/Salary_dataset.csv`
- **Columns:**
  - `YearsExperience`: Number of years of professional experience
  - `Salary`: Annual salary (target variable)

## Notebooks
- **Salary Dataset.ipynb**: Main notebook containing all code for data loading, EDA, visualization, model training, and evaluation.

## Key Steps
1. **Import Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
2. **Load Data**: Read the CSV file into a pandas DataFrame
3. **Data Cleaning**: Remove unnecessary columns if present
4. **EDA & Visualization**:
   - Display data samples and types
   - Visualize relationships (scatter plot, regression line, histogram, boxplot, KDE)
5. **Model Preparation**:
   - Split data into features (X) and target (y)
   - Train-test split
6. **Model Training**:
   - Fit a Linear Regression model
   - Predict on test data
7. **Evaluation**:
   - Calculate MAE, MSE, RMSE
   - Visualize predictions

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install requirements with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Open `Salary Dataset.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells to execute the analysis and view results.

## Output
- Visualizations of salary vs. experience
- Regression model performance metrics
- Plots of predictions and data distributions

## Author
- Himanshu Heda

---
This project is for educational purposes and demonstrates basic regression analysis and data visualization in Python.
