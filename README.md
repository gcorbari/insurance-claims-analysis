# insurance-claims-analysis
 
### Overview
This project develops a machine learning end-to-end solution to automate the detection of suspicious patterns. 
 
### Aim 
Identification of fraudulent insurance claims with a robust classification approach, prioritizing precision and model interpretability to ensure that high-risk flags are actionable for human investigators.
 
### Methods
- Data Engineering (Cleaning, Imputation)
- Feature Engineering
- Exploratory Data Analysis
- Feature Selection (Recursive Feature Elimination)
- Classification (Linear and Decision Tree models)
- Benchmarking and Interpretation (SHAP)
 
### Data Source
The data used in this project come from the *insurance_claims* dataset, which contains 1,000 records of insurance claims with various features such as policy details, incident specifics, and a fraud flag.
* Dataset Link: [insurance_claims](https://data.mendeley.com/datasets/992mh7dk9y/2)
* Target Variable: `fraud_reported` (Binary: Yes/No)
 
### Requirements
This project was developed using **Python 3.11.15**. To ensure full reproducibility, the versions of the python modules used in this analysis are listed in the [requirements.txt](https://github.com/gcorbari/insurance-claims-analysis/blob/main/requirements.txt) file