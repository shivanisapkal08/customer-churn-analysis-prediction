##### \# **Customer Churn Analysis and Prediction**



\## **Project Overview**

An end-to-end data analysis and machine learning project using the IBM Telco Customer Churn dataset to identify customer churn patterns, predict potential churners, and derive actionable customer-retention insights.



\## **Objectives**

\- Explore customer characteristics and identify churn-associated patterns.

\- Build and compare machine learning classification models.

\- Interpret model predictions using SHAP explainability.

\- Present findings through an Excel dashboard and prepare data for future Power BI reporting.



\## **Tools and Technologies**

\- \*\*Language:\*\* Python

\- \*\*Data Analysis:\*\* Pandas, NumPy

\- \*\*Machine Learning:\*\* Scikit-learn, Logistic Regression, Random Forest

\- \*\*Explainability:\*\* SHAP

\- \*\*Visualization and Reporting:\*\* Matplotlib, Seaborn, Microsoft Excel

\- \*\*Notebook Environment:\*\* Jupyter Notebook



\## **Dataset**

The project uses the IBM Telco Customer Churn dataset, containing 7,043 customer records and 21 original columns covering customer demographics, services, contracts, charges, tenure, and churn status.



\## **Methodology**

1\. Cleaned the dataset and handled blank `TotalCharges` values for customers with zero tenure.

2\. Performed exploratory data analysis to examine churn by contract type, tenure, payment method, and internet service.

3\. Prepared numerical and categorical features using scaling and one-hot encoding.

4\. Trained and evaluated Logistic Regression and Random Forest models using a stratified 80/20 train-test split.

5\. Used SHAP to interpret the features influencing model predictions.

6\. Created an Excel dashboard with KPI metrics, PivotCharts, and business insights.



\## **Model Results**

\*\*Best-performing model: Logistic Regression\*\*



| Metric | Test Result |

|---|---:|

| Accuracy | 80.55% |

| Precision | 65.72% |

| Recall | 55.88% |

| F1-score | 60.40% |

| ROC-AUC | 84.21% |



Logistic Regression outperformed the Random Forest model on the evaluated test metrics.



\## **Key Findings**

\- Month-to-month contracts had a churn rate of 42.71%, compared with 11.27% for one-year contracts and 2.83% for two-year contracts.

\- Customers who churned had a median tenure of 10 months, compared with 38 months for customers who stayed.

\- Electronic check users had the highest observed churn rate at 45.29%.

\- Fiber-optic customers had an observed churn rate of 41.89%.



These are associations observed in the dataset and do not establish causation.



\## **Dashboard**

An Excel dashboard was created to present customer metrics, churn patterns, and estimated monthly charges associated with predicted churners. Power BI dashboard development is planned as a future enhancement.



\## **Limitations**

\- Model performance is evaluated on a held-out test set.

\- Full-dataset predictions include training records and should be treated as exploratory.

\- Estimated monthly charges associated with predicted churners are not guaranteed revenue losses or savings.

\- The dataset does not establish future churn over a specific forecast period.



