
# 📊 Customer Churn Prediction

This project focuses on analyzing and predicting **customer churn** using the **Telco Customer Churn dataset** from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
The goal is to understand why customers leave and to build a machine learning model that can predict churn based on customer behavior and account information.

---

## 📁 Repository Structure

| File                                   | Description                                                                                                     |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| `Customer_Churn.ipynb`                 | Main Jupyter Notebook containing the full analysis, visualizations, preprocessing, and model training pipeline. |
| `Telco-Customer-Churn.csv` | Dataset file downloaded from Kaggle and included in the repo.                                                   |
| `README.md`                            | Project documentation.                                                                                          |

---

## 📖 Dataset Overview

**Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset includes information about a telecom company’s customers, such as:

* **Demographics:** Gender, SeniorCitizen, Partner, Dependents
* **Account Info:** Tenure, Contract Type, Payment Method, Charges
* **Services:** Internet Service, Online Security, Tech Support, etc.
* **Target Variable:** `Churn` — whether the customer left the company (`Yes` or `No`)

---

## 🧠 Project Objectives

1. **Data Preprocessing**

   * Handle missing and inconsistent data
   * Encode categorical variables
   * Scale/normalize numerical features

2. **Exploratory Data Analysis (EDA)**

   * Visualize churn distribution and key factors
   * Correlation analysis and categorical breakdowns

3. **Model Building**

   * Machine learning models used:

     * Logistic Regression
     * Decision Tree
     * Random Forest
     * LightGBM
   * Evaluated using accuracy, precision, recall, and F1-score

4. **Insights & Recommendations**

   * Identify high-risk customer groups
   * Suggest strategies to reduce churn (e.g., longer contracts, better support, loyalty offers)

---

## 📈 Model Performance

| Metric        | Score      |
| ------------- | ---------- |
| **Accuracy**  | ~0.78–0.80 |
| **Precision** | ~0.79      |
| **Recall**    | ~0.78      |
| **F1-Score**  | ~0.79      |

The models achieve around **80% accuracy**, indicating solid performance in predicting customer churn based on the provided features.

---

## ⚙️ Installation & Requirements

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```
Or 

Use  `requirements.txt` file for easier setup.

---

## 🚀 How to Run the Notebook

1. Clone this repository:

   ```bash
   git clone https://github.com/priyanshchandr/Customer_Churn.git
   cd customer-churn
   ```

2. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook "Customer_Churn.ipynb"
   ```

3. Run all cells sequentially to reproduce the analysis and results.

---

## 📚 References

* [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* [Scikit-learn Documentation](https://scikit-learn.org/stable/)
* [LightGBM Documentation](https://lightgbm.readthedocs.io/)

---

## 🧾 License

This project is intended for educational and research use.
Dataset © Kaggle and respective owners.

---
