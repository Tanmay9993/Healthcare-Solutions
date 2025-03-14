# Hospital Resource Forecasting

This repository contains a suite of forecasting models aimed at optimizing critical hospital resources. By leveraging historical clinical data, the projects are designed to provide actionable insights to improve operational efficiency and patient care in hospitals.

## Projects Overview

### 1. Bed Occupancy & ICU Demand
- **Objective:** Predict the number of admissions, discharges, and ICU occupancy trends.
- **Models Used:** ARIMA, SARIMA, and LSTM.
- **Impact:** Helps optimize bed turnover, prevent ICU overcrowding, and improve resource allocation.

### 2. Staffing Needs
- **Objective:** Forecast nurse and doctor demand per shift based on peak patient volumes.
- **Models Used:** Random Forest and XGBoost.
- **Impact:** Aims to prevent understaffing, optimize shift scheduling, and reduce staff burnout.

### 3. Ventilator & Oxygen Needs
- **Objective:** Estimate demand based on critical patient admissions and diagnoses.
- **Models Used:** Regression and Classification.
- **Impact:** Ensures critical care readiness by avoiding shortages of ventilators and oxygen supplies.

## Aim & Benefits

The goal of these forecasting models is to equip hospital administrators with data-driven insights that:
- **Optimize Resource Allocation:** By predicting bed occupancy, staffing, and equipment needs.
- **Enhance Patient Care:** Through improved operational planning and readiness.
- **Reduce Operational Costs:** By minimizing resource wastage and mitigating the risks of overcrowding or understaffing.


<h1>Data Source</h1> 
This project uses the [MIMIC-IV Clinical Database Demo (version 2.2)](https://physionet.org/content/mimic-iv-demo/2.2/).  

<h3>Database:</h3>
Johnson, A., Bulgarelli, L., Pollard, T., Horng, S., Celi, L. A., and Mark, R. (2023) 'MIMIC-IV Clinical Database Demo' (version 2.2), PhysioNet. 
Available at: https://doi.org/10.13026/dp1f-ex47.

<h3>Physionet</h3>
Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P.C., Mark, R., Mietus, J.E., Moody, G.B., Peng, C.K. and Stanley, H.E., 
2000. PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 
101 (23), pp. e215–e220.
