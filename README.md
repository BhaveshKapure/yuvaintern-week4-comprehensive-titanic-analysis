# Yuvaintern Week 4 - Comprehensive Titanic Data Analysis

## Project Overview

This repository contains the final Week 4 project for the Yuvaintern internship. The project integrates the work completed during Weeks 1, 2, and 3 into one complete data analysis workflow using R.

The project uses the Titanic passenger dataset and covers data cleaning, exploratory analysis, data visualization, statistical hypothesis testing, and predictive modeling.

---

## Project Objectives

The main objectives of this project are:

- Clean and preprocess a real-world dataset.
- Identify and handle missing values.
- Detect and investigate potential outliers.
- Perform exploratory data analysis.
- Create meaningful visualizations.
- Conduct statistical hypothesis tests.
- Build a predictive classification model.
- Evaluate model performance.
- Communicate data-driven insights clearly.
- Document the complete workflow professionally.

---

## Project Workflow

The complete project follows this workflow:

Raw Data
↓
Data Cleaning
↓
Data Transformation
↓
Exploratory Analysis
↓
Data Visualization
↓
Hypothesis Testing
↓
Predictive Modeling
↓
Cross-Validation
↓
Model Evaluation
↓
Final Insights and Recommendations

---

## Week 1 - Data Cleaning and Preliminary Analysis

Week 1 focused on preparing the Titanic dataset for analysis.

Main activities included:

- Dataset inspection
- Missing-value analysis
- Median imputation for Age
- Mode imputation for Embarked
- Cabin missingness analysis
- CabinKnown feature creation
- Duplicate checking
- IQR-based outlier detection
- Categorical encoding
- Min-max normalization
- Descriptive statistics

### Important findings

- The dataset contains 891 passenger records.
- Age contained missing observations.
- Cabin contained a large proportion of missing observations.
- Embarked contained only a small number of missing values.
- No exact duplicate records were found.
- Fare contained potential high-value outliers.

---

## Week 2 - Data Visualization and Insight Communication

Week 2 focused on communicating analytical findings through visualizations.

The project includes:

- Bar charts
- Histograms
- Scatter plots
- Line charts
- Boxplots
- Category comparisons
- Distribution analysis

### Main visual insights

The visual analysis showed substantial differences in observed survival rates according to passenger sex and class.

Different chart types were selected according to the analytical question so that the results could be understood by both technical and non-technical audiences.

---

## Week 3 - Statistical Analysis and Predictive Modeling

Week 3 introduced statistical inference and predictive modeling.

### Statistical methods

- Shapiro-Wilk normality test
- Chi-square test of independence
- Wilcoxon rank-sum test
- Pearson correlation

### Predictive model

A logistic regression classification model was developed to predict passenger survival.

Predictors included:

- Passenger class
- Sex
- Age
- Siblings/spouses
- Parents/children
- Fare
- Embarkation port
- Cabin availability

### Model validation

- 80/20 stratified train-test split
- 5-fold cross-validation
- Confusion matrix
- Accuracy
- Precision
- Recall
- F1 score
- ROC curve
- ROC-AUC

---

## Week 4 - Comprehensive Final Report

Week 4 integrates all previous work into one complete report.

The final report contains:

- Executive summary
- Dataset overview
- Data preparation methodology
- Visualization analysis
- Statistical analysis
- Predictive modeling
- Model evaluation
- Integrated findings
- Practical implications
- Challenges encountered
- Recommendations
- Future work
- Final conclusion

---

## Final Model Performance

The logistic regression model achieved approximately:

| Metric | Result |
|---|---:|
| Accuracy | 81.0% |
| Precision | 77.8% |
| Recall | 71.0% |
| F1 Score | 74.2% |
| ROC-AUC | 84.0% |

These values indicate that the model has useful predictive ability while remaining relatively interpretable.

---

## Key Findings

1. Survival rates differed substantially between male and female passengers.
2. Passenger class was strongly associated with survival.
3. Fare distributions differed between survivors and non-survivors.
4. Age and Fare showed only a modest linear relationship.
5. Logistic regression provided useful survival predictions.
6. Cross-validation was used to assess model stability.

---

## Repository Structure

```text
yuvaintern-week4-comprehensive-titanic-analysis/
│
├── README.md
│
├── report/
│   └── Yuvaintern_Task4_Comprehensive_Final_Report.docx
│
├── data/
│   └── titanic_cleaned.csv
│
├── R/
│   ├── titanic_week1_analysis.R
│   ├── titanic_week2_visualization.R
│   └── titanic_week3_statistical_modeling.R
│
└── visualizations/
    ├── week1/
    ├── week2/
    └── week3/
