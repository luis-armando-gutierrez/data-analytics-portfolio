# Customer Churn Analysis (Supervised Learning)

## Project Overview
This project focuses on predicting customer churn using supervised learning techniques. The objective is to identify customers at risk of leaving a service, enabling data-driven decisions for retention strategies.

The analysis was developed as part of a supervised learning project and emphasizes data preparation, class imbalance handling, model training, and evaluation.

---

## Business Problem
Customer churn directly impacts revenue and long-term growth. By predicting which customers are more likely to churn, businesses can proactively design retention actions and optimize customer lifetime value.

---

## Data Preparation
- Performed initial data inspection and cleaning.
- Handled missing values and ensured data consistency.
- Analyzed feature distributions and relationships with the target variable.
- Identified **class imbalance** in the churn target.

---

## Modeling Approach
- Formulated the problem as a **binary classification task**.
- Trained baseline supervised learning models.
- Addressed class imbalance using:
  - **Upsampling techniques**
  - **Class weight balancing**
- Compared model performance with and without balancing strategies.

---

## Model Evaluation
Models were evaluated using appropriate classification metrics, focusing on performance under imbalanced data conditions. Special attention was given to metrics beyond accuracy to better capture churn prediction performance.

---

## Key Insights
- Class imbalance significantly affects churn prediction performance.
- Applying balancing techniques improves the model’s ability to correctly identify churned customers.
- Proper data preparation and evaluation are critical for reliable supervised learning results.

---

## Tools & Technologies
- Python
- pandas, NumPy
- scikit-learn
- Jupyter Notebook

---

## Outcome
The project demonstrates a complete supervised learning workflow, from data preparation to model evaluation, highlighting practical challenges such as class imbalance and their impact on real-world business problems.

