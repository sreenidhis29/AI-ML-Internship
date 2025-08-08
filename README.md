# AI-ML-Internship (S Shreenidhi)

## Task 1: Data Cleaning & Preprocessing

## Objective
Clean and prepare the Titanic dataset for machine learning.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Steps Performed
- Loaded and explored the Titanic dataset
- Handled missing values (Age, Embarked), dropped Cabin
- Encoded categorical variables (Sex, Embarked)
- Normalized numerical features using Min-Max scaling
- Visualized and removed outliers using IQR method
- Exported cleaned data to `titanic_cleaned.csv`

## Output Files
- `AI_ML_Task1_Data_Cleaning.ipynb`
- `titanic_cleaned.csv`

# Task 2: Exploratory Data Analysis (EDA)

## Objective
Explore and understand the Titanic dataset using statistical summaries and visualizations.

## Tools Used
Python, Pandas, Seaborn, Matplotlib, Plotly

## Steps Performed
- Generated summary statistics for all features
- Plotted histograms and boxplots for numerical columns
- Created a correlation heatmap and pairplot to observe relationships
- Built an interactive scatter plot (Age vs Fare) using Plotly
- Identified key patterns such as survival based on age, fare, and class

## Output Files
- `AI_ML_Task2_EDA.ipynb`: Notebook with all analysis and visualizations

# Task 3: Linear Regression

## Objective
Build and evaluate a simple and multiple linear regression model using a house price dataset.

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib

## Steps Performed
- Loaded the House Price dataset
- Split data into training and testing sets
- Trained a Linear Regression model
- Evaluated using MAE, MSE, and R² score
- Printed model coefficients
- Plotted actual vs predicted values

## Output Files
- `AI_ML_Task3_Linear_Regression.ipynb`: Notebook with all code, metrics, and plots

# Task 4: Classification with Logistic Regression

## Objective
Build a binary classifier using logistic regression on the Breast Cancer Wisconsin dataset.

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib

## Steps Performed
- Loaded and explored the dataset
- Standardized features and split data into train/test sets
- Trained a Logistic Regression model
- Evaluated using confusion matrix, precision, recall, F1-score, and ROC-AUC
- Explained sigmoid function and visualized threshold tuning

## Output Files
- `AI_ML_Task4_Logistic_Regression.ipynb`: Contains all preprocessing, model training, evaluation, and visualizations
