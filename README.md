# Medical Insurance Cost Analysis: Exploratory Data Analysis (EDA)

## Project Overview
This repository contains an in-depth Exploratory Data Analysis (EDA) of medical insurance billing data. The primary objective is to investigate the statistical properties of the dataset, identify underlying distributions, and uncover the primary demographic and lifestyle drivers of healthcare costs through univariate, bivariate, and multivariate analysis.

## Dataset Information
The dataset comprises demographic statistics, physical health metrics, and the resulting medical insurance charges for various beneficiaries. 

* **Target Variable:** 
  * `charges` (Continuous): Individual medical costs billed by the health insurance provider.
* **Predictor Variables:**
  * `age` (Discrete): Age of the primary beneficiary.
  * `sex` (Categorical): Gender of the insurance contractor (Male/Female).
  * `bmi` (Continuous): Body Mass Index, a measure of body fat based on height and weight (kg/m²).
  * `children` (Discrete): Number of dependents covered by the health insurance plan.
  * `smoker` (Categorical): Smoking status of the beneficiary (Yes/No).
  * `region` (Categorical): The beneficiary's residential area in the US (Northeast, Southeast, Southwest, Northwest).

*(Note: The dataset was sourced from [Kaggle's Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance) and contains 1,338 records.)*

## Analytical Objectives
- **Data Quality Assessment:** Identify missing values, structural errors, and statistical outliers within the dataset.
- **Distribution Analysis:** Evaluate the probability distributions of continuous features such as Age, BMI, and Charges.
- **Correlation Mapping:** Quantify the relationships between independent variables and the target variable (`charges`).
- **Risk Factor Isolation:** Visualize and assess how specific lifestyle choices (e.g., smoking) and physical conditions (e.g., obesity) interact to impact insurance premiums.

## Tech Stack & Libraries
- **Language:** Python 
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook 

## Key Insights & Findings
* **The Smoking Penalty:** Smoking status is the most significant predictor of medical charges. The data reveals a distinct stratification where smokers incur substantially higher premiums compared to non-smokers, regardless of age.
* **Age-Cost Correlation:** There is a steady, positive correlation between age and baseline insurance charges, reflecting natural increases in healthcare dependency over time.
* **The Compounding Effect of BMI:** While high BMI alone shows a moderate effect on costs, the interaction between obesity (BMI > 30) and smoking yields the highest-cost cohort in the entire dataset.

## Local Setup & Execution

To run this analysis locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/bhavyadharod2707/Medical_Insurance_Analysis.git](https://github.com/bhavyadharod2707/Medical_Insurance_Analysis.git)
