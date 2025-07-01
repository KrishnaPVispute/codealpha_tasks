# codealpha_tasks
# Credit_Scoring_model
## Overview

> Predict creditworthiness of individuals based on past financial behavior using classification algorithms such as Logistic Regression and Random Forest. The goal is to help financial institutions and lenders assess risk more accurately.

---

##  Features in the Dataset

| Feature                        | Description                                     |
|-------------------------------|-------------------------------------------------|
| `Income`                      | Annual income (in ₹)                           |
| `Debt`                        | Total outstanding debt                         |
| `Credit_History_Years`        | Number of years of credit history              |
| `Credit_Mix`                  | Count of credit types used                     |
| `New_Credit_Apps`             | Applications made in the last 6 months         |
| `On_Time_Payments`            | Number of on-time payments                     |
| `Late_Payments`               | Number of late payments                        |
| `Payment_Ratio`               | Ratio of on-time to total payments (engineered)|
| `Creditworthiness`            | Target label: 1 = Good, 0 = Bad                |

---

##  Model Performance (Random Forest)

| Metric         | Value    |
|----------------|----------|
| **Accuracy**   | 97.4%    |
| **Precision**  | 97.5%    |
| **Recall**     | 99.6%    |
| **F1 Score**   | 98.6%    |
| **ROC AUC**    | 99.7%    |

---

## Tech Stack

- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- (Optional) Streamlit or Flask for UI




Accuracy: 0.9740
Precision: 0.9751
Recall: 0.9961
F1 Score: 0.9855
ROC AUC Score: 0.9973




