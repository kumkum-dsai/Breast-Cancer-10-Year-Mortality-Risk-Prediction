# Breast Cancer 10-Year Mortality Risk Prediction

An end-to-end machine learning and survival analysis project using the METABRIC breast cancer dataset to explore factors associated with long-term mortality risk.

## Project Overview

This project combines exploratory data analysis, feature engineering, machine learning classification, survival analysis, Cox proportional hazards modeling, SHAP explainability, and a Power BI dashboard.

> **Important:** This project is for educational and analytical purposes only. It is not a clinical diagnostic or treatment tool and should not be used for medical decision-making.

## Objective

The goal is to analyze patient and tumor characteristics and build machine learning models that classify 10-year mortality risk, while also studying survival patterns and model explainability.

## Dataset

- Source file: `Breast Cancer METABRIC.csv`
- Records: 2,509 patients
- Original columns: 34
- Includes demographic, tumor, treatment, survival, and clinical characteristics.

## Workflow

1. Data loading and quality checks
2. Exploratory data analysis
3. Missing-value handling and preprocessing
4. Feature engineering and encoding
5. Train/test split
6. Model training and evaluation
7. ROC-AUC comparison
8. Survival analysis
9. Cox proportional hazards analysis
10. SHAP-based model explainability
11. Power BI dashboard development

## Machine Learning Results

| Model | Accuracy | ROC-AUC |
|---|---:|---:|
| Logistic Regression | 95.02% | 98.55% |
| SVM | 95.02% | 98.50% |
| Decision Tree | 95.22% | 97.50% |

The Decision Tree achieved the highest accuracy, while Logistic Regression achieved the highest ROC-AUC among the evaluated models.

## Survival Analysis

Kaplan-Meier survival analysis and a Cox proportional hazards model were used to investigate survival patterns and the relationship between patient/tumor characteristics and time-to-event outcomes.

## Explainability

SHAP was used to understand which features contributed most strongly to individual and overall model predictions. This helps make the model output more interpretable rather than treating predictions as a black box.

## Power BI Dashboard

The project includes an interactive Power BI dashboard covering key patient, tumor, treatment, survival, and mortality-risk insights.

## Repository Structure

```text
Breast-Cancer-10-Year-Mortality-Risk-Prediction/
├── README.md
├── data/
│   └── Breast Cancer METABRIC.csv
├── notebooks/
│   └── Breast_Cancer_10year_Mortality_Risk_Prediction.ipynb
├── dashboard/
│   └── Breast Cancer 10 Year Mortality Risk Prediction Dashboard.pbix
├── presentation/
│   └── Breast_Cancer_10year_Mortality_Risk_Prediction.pptx
├── images/
│   ├── dashboard.png
│   ├── model_comparison.png
│   ├── roc_curve.png
│   ├── survival_curve.png
│   └── shap_analysis.png
└── requirements.txt
```

## Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP, Lifelines, Jupyter Notebook, Power BI, and Excel/CSV data handling.

## How to Run

1. Clone the repository.
2. Install the dependencies from `requirements.txt`.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Update the dataset path if required.
5. Run the notebook cells sequentially.
6. Open the `.pbix` file in Power BI Desktop to explore the dashboard.

## Limitations

- The dataset is observational and may contain missing or noisy clinical information.
- Model performance on this dataset does not guarantee performance on other populations.
- The project focuses on analytical prediction and does not establish clinical causation.

## Author

**Kumkum Yadav**  
Data Analyst | Data Science & AI
