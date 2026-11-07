# Cancer_Mobility-

# Cancer Mortality Rate Prediction Using Machine Learning

## Project Overview

Cancer is one of the major health challenges worldwide. Understanding factors associated with cancer mortality can help researchers analyze patterns and trends in cancer-related deaths.

This project uses Machine Learning regression algorithms to predict cancer mortality rates based on the available dataset features.

The project implements Multiple Linear Regression and Polynomial Regression models and compares their performance using different evaluation metrics.

## Objectives

- Analyze the cancer mortality dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Identify numerical and categorical features.
- Apply categorical encoding techniques.
- Select important features for prediction.
- Build regression models.
- Evaluate and compare model performance.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development environment |

## Machine Learning Algorithms

The following regression algorithms are implemented:

1. **Multiple Linear Regression:** Predicts cancer mortality rate using multiple independent variables.
2. **Polynomial Regression (Degree 2):** Captures nonlinear relationships using second-degree polynomial features.
3. **Polynomial Regression (Degree 3):** Captures more complex relationships using third-degree polynomial features.

## Project Workflow

### 1. Data Collection
Load the cancer mortality dataset using Pandas.

### 2. Data Exploration
- View the first and last records.
- Check dataset dimensions.
- Understand column names and data types.
- Generate descriptive statistics.

### 3. Data Preprocessing
- Remove duplicate records.
- Handle missing and invalid values.
- Convert columns into appropriate data types.
- Separate numerical and categorical features.
- Encode categorical variables using One-Hot Encoding.
- Identify potential outliers.

### 4. Feature Selection
Select important numerical features based on their correlation with the target variable.

### 5. Model Building
Split the dataset into training and testing sets using an 80:20 ratio.

Train the following models:
- Multiple Linear Regression
- Polynomial Regression Degree 2
- Polynomial Regression Degree 3

### 6. Model Evaluation
Evaluate model performance using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

### 7. Model Comparison
Compare the evaluation metrics of all three models to identify the best-performing regression approach.

## Target Variable

`target_deathrate`

The target variable represents the cancer mortality rate that the machine learning models aim to predict.

## Dataset

The project uses a cancer mortality CSV dataset (`cancer_reg.csv`).

Place the dataset in your project directory before running the notebook.

## Installation and Setup

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the project directory

```bash
cd cancer-mortality-prediction
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open and run the notebook

Open `cancer.ipynb` and execute the cells in sequence after configuring the dataset file path.

## Project Structure

```text
Cancer-Mortality-Prediction/
│
├── cancer.ipynb
├── cancer_reg.csv
└── README.md
```

## Results

The project compares Multiple Linear Regression and Polynomial Regression models of degrees 2 and 3.

The evaluation results include:
- MAE
- MSE
- RMSE
- R² Score

The best-performing model can be selected by comparing the evaluation metrics obtained during execution.

## Future Improvements

- Experiment with Random Forest Regression and Decision Tree Regression.
- Perform advanced feature selection.
- Apply cross-validation.
- Optimize model hyperparameters.
- Develop an interactive prediction interface.
- Explore additional machine learning algorithms.

## Conclusion

This project demonstrates how machine learning regression techniques can be used to analyze cancer mortality data and predict cancer death rates.

By comparing multiple regression models, the project aims to understand how different algorithms perform on the given dataset and identify an appropriate predictive model.

## Disclaimer

This project is developed for educational and research purposes only. Predictions should not be used as a substitute for professional medical advice, diagnosis, or treatment.
