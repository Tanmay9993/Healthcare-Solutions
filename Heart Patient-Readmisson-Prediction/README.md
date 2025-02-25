<h1>Predicting Patient Readmissions to Prevent HRRP Penalties</h1>

<h3>📌 Problem Statement</h3>
Preventable hospital readmissions are a major challenge in healthcare, leading to financial penalties under the Hospital Readmissions Reduction Program (HRRP). Hospitals with high 30-day readmission rates for conditions like heart failure, pneumonia, and COPD face up to a 3% reduction in Medicare reimbursements. Identifying high-risk patients before discharge is essential to reducing readmission rates and improving patient care.


<h3>🏥 Solution Approach</h3>
This project utilizes machine learning and predictive analytics to identify patients at risk of readmission within 28 days. The approach includes:

* Data Analysis & Visualization → Understanding key factors influencing readmissions.
* Feature Selection → Using SHAP & Random Forest to extract the most important features.
* Model Development → Training multiple ML models (Logistic Regression, SVM, KNN, Random Forest, XGBoost, LightGBM).
* Handling Class Imbalance → Implementing SMOTE (Synthetic Minority Over-sampling Technique) to improve recall and ensure high-risk patients are correctly identified.


This solution enables hospitals to proactively intervene with better discharge planning, targeted monitoring, and improved patient care—ultimately helping to reduce readmissions and mitigate HRRP penalties.


<h1>Data Source</h1> 
This project uses the [Hospitalized patients with heart failure: integrating electronic healthcare records and external outcome data](https://physionet.org/content/heart-failure-zigong/1.3/).  

<h3>Database:</h3>
Zhang, Z., Cao, L., Zhao, Y., Xu, Z., Chen, R., Lv, L., and Xu, P. (2022) 'Hospitalized patients with heart failure: integrating electronic healthcare records and external outcome data' 
(version 1.3), PhysioNet. Available at: https://doi.org/10.13026/5m60-vs44.
<br></br>
Zhang, Z., Cao, L., Chen, R. et al. Electronic healthcare records and external outcome data for hospitalized patients with heart failure. 
Sci Data 8, 46 (2021). https://doi.org/10.1038/s41597-021-00835-9

<h3>Physionet</h3>
Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P.C., Mark, R., Mietus, J.E., Moody, G.B., Peng, C.K. and Stanley, H.E., 
2000. PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 
101 (23), pp. e215–e220.
