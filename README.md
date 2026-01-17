# Shipment Delivery Prediction Using Machine Learning

This repository contains a machine learning project that predicts whether a shipment will be delivered on time based on customer, product, and logistics-related features. The project includes complete data preprocessing, exploratory data analysis, feature engineering, model development, and evaluation.

---

## ## Project Overview

Timely delivery is a key factor in logistics and supply chain management. This project uses a structured dataset to classify shipments as **Reached on Time (1)** or **Not Reached on Time (0)**.

The Notebook (`ml.ipynb`) covers:

- Data loading and cleaning  
- Handling missing values  
- Encoding categorical features  
- Outlier detection and treatment  
- Feature scaling  
- Model training and evaluation  
- Performance comparison  

---

## Dataset Features

| Feature | Description |
|--------|-------------|
| Warehouse_block | Warehouse location (A, B, C, D, F) |
| Mode_of_Shipment | Shipment mode: Road, Flight, Ship |
| Customer_care_calls | Number of customer care calls |
| Customer_rating | Rating provided by the customer (1–5) |
| Cost_of_the_Product | Product cost |
| Prior_purchases | Customer purchase history count |
| Product_importance | low / medium / high |
| Gender | M / F |
| Discount_offered | Discount percentage |
| Weight_in_gms | Product weight |
| Reached_on_Time_Y_N | Target variable (0 = Late, 1 = On Time) |

---

## Objective

To build and evaluate machine learning models that accurately classify whether a shipment reaches on time using the given set of features.

---

## Techniques Used

- Label Encoding and One-Hot Encoding  
- Z-score and IQR-based outlier handling  
- Train–test split  
- StandardScaler normalization  
- Logistic Regression  
- Random Forest  
- Support Vector Machine  
- Confusion Matrix, Accuracy, Precision, Recall, F1-score  

---

## Project Structure

