# Diabetes Risk Prediction & Fairness Analysis

This project analyzes diabetes risk factors using machine learning and fairness evaluation techniques on CDC BRFSS health survey data. The analysis explores how lifestyle, physiological, and demographic factors contribute to diabetes prevalence while also assessing whether predictive models perform equitably across demographic groups.

## Project Objective

The primary goal of this project was to investigate:

* Which lifestyle and health-related factors are most strongly associated with diabetes risk
* How accurately machine learning models can classify diabetes outcomes
* Whether predictive performance differs across demographic groups
* How fairness mitigation techniques influence model equity and performance

This project combines exploratory data analysis, predictive modeling, and fairness evaluation within a healthcare analytics context.

---

## Dataset

**Dataset:** CDC Diabetes Health Indicators Dataset (BRFSS 2015)
**Source:** CDC Behavioral Risk Factor Surveillance System (BRFSS)

The dataset contains over 250,000 survey responses with health indicators, demographic information, and lifestyle-related variables associated with diabetes risk.

### Example Variables

* BMI
* High Blood Pressure
* High Cholesterol
* Physical Activity
* Smoking Status
* Heavy Alcohol Consumption
* Age
* Gender
* Diabetes Status

---

## Methods & Analysis

### Exploratory Data Analysis

The project examined:

* Diabetes prevalence in the population
* Relationships between BMI and diabetes
* Interactions between physical activity and BMI
* Diabetes prevalence across age and gender groups
* Lifestyle-related diabetes risk patterns

### Predictive Modeling

Three machine learning classification models were trained and compared:

* Decision Tree
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

Models were evaluated using:

* Accuracy
* Sensitivity (Recall)
* Specificity
* ROC/AUC
* Cross-validation performance

### Feature Importance

A simplified decision tree model was used to identify the most influential lifestyle-related predictors of diabetes risk.

### Fairness Evaluation

The project also evaluated whether predictive performance differed across demographic groups and discussed ethical considerations related to healthcare machine learning systems.

---

## Key Findings

* Diabetes prevalence increased substantially with age
* High blood pressure emerged as the strongest predictor of diabetes risk
* BMI and high cholesterol were also highly influential
* Physical activity demonstrated a protective relationship against diabetes
* Support Vector Machine (SVM) achieved the strongest overall predictive performance
* Small demographic differences may still influence model fairness and prediction outcomes

---

## Files Included

| File                                              | Description                                                                           |
| ------------------------------------------------- | ------------------------------------------------------------------------------------- |
| `Diabetes-Risk-Analysis-Improved.Rmd`             | Full R Markdown report containing code, analysis, visualizations, and interpretations |
| `Diabetes-Risk-Analysis-Improved.html`            | Knitted HTML report                                                                   |
| `Diabetes Risk Prediction Presentation.pdf`       | Presentation slides summarizing the project findings                                  |
| `diabetes_indicators.csv`                         | Dataset used for analysis                                                             |

---

## Technologies Used

* R
* ggplot2
* caret
* dplyr
* tidyr
* Scikit-learn concepts
* Fairmodels

