# Student Performance Analysis and Prediction

## Project Overview
This project analyzes student academic performance data to identify key factors influencing their grades and to build predictive models that estimate final performance. The aim is to help educators and administrators make data-driven decisions to support student success.

The project has two key components:
1. Exploratory Data Analysis (EDA)
2. Predictive Modeling using Machine Learning

---

## Dataset
- Includes information about student demographics, study habits, family background, and academic performance.
- Columns include: `gender`, `parental level of education`, `lunch`, `test preparation course`, `math score`, `reading score`, `writing score`, etc.

---

## Tools & Technologies
- **Python**
- **Pandas, NumPy** – Data preprocessing
- **Matplotlib, Seaborn** – Visualizations
- **Scikit-learn** – Model building (regression/classification)
- **Jupyter Notebook** – Development and presentation

---

## Notebooks
- `1. EDA STUDENT PERFORMANCE.ipynb`: Performs data exploration, feature correlation analysis, and visualizations to uncover insights.
- `2. MODEL TRAINING.ipynb`: Builds and evaluates regression models to predict student scores and classification models to predict pass/fail status.

---

## Key Insights
- Reading and writing scores are highly correlated with math scores.
- Test preparation and parental education level show noticeable impact on student performance.
- Gender and lunch type also show moderate influence on outcomes.

---

## Modeling Summary
- Regression Models: Linear Regression, Random Forest, XGBoost
- Classification Models: Logistic Regression, Random Forest Classifier
- Metrics Used: RMSE, R² Score, Accuracy, Confusion Matrix

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/HemanthK7227/student-performance-predictor.git
   cd student-performance-predictor
