# 🧠 DM Project: Predicting Socioeconomic Outcomes Using Country-Level Data

## 📌 Overview

This project involves a data mining workflow that aims to analyze and predict outcomes using socioeconomic and demographic data from various countries. The main objective is to understand relationships between IQ, income, education, temperature, and other features, applying classification techniques and evaluating model performance.

## 📂 Dataset Description

Two main datasets are merged for analysis:

- `IQ.csv`: Contains IQ scores per country
- `IncTmp.csv`: Includes income, temperature, and education expenditure data

The final merged dataset includes features like:
- `Id`: Country identifier
- `country`: Name of the country
- `IQ`: Average IQ score
- `education_expenditure`: Percentage of GDP spent on education
- `avg_income`: Average income of the population
- `avg_temp`: Average temperature

## 🔧 Steps Performed

### 1. Data Preparation
- **1.1 Data Integration**: Merging datasets using `Id` and `country`
- **1.2 Data Shuffling**: Randomizing rows to eliminate ordering bias
- **1.3 Data Cleaning**: Removing duplicates, checking missing values, and validating data types

### 2. Feature Selection
- Using **Information Gain** and **Chi-Square Test** to determine the most relevant features

### 3. Data Splitting
- Splitting into input features `X` and target variable `Y`
- Applying train-test split using `train_test_split`

### 4. Modeling
Applied the following classifiers:
- Logistic Regression (LR)
- Linear Discriminant Analysis (LDA)
- K-Nearest Neighbors (KNN)
- Naive Bayes (NB)
- Support Vector Machine (SVM)

### 5. Tuning & Standardization
- Standardizing feature scales
- Hyperparameter tuning for model optimization

### 6. Evaluation
- Comparing model accuracy using cross-validation
- Visualizing performance via boxplots
- Analyzing classification results and AUC scores

## 🧪 Dependencies

The following Python libraries are required:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install via pip:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📊 Results

- Performance of different classifiers was evaluated and compared.
- The best performing models were selected based on AUC and classification accuracy.

## 📁 Project Structure

```
├── data/
│   ├── IQ.csv
│   └── IncTmp.csv
├── DM_project.ipynb
└── README.md
```

## 👤 Author

- Name: *[Your Name Here]*
- Course: Data Mining
- University: *[Your Institution]*
