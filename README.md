# 🚗 Car Price Prediction using Multiple Linear Regression

![Task Banner](tsk-2.jpg)

## 📌 Task Description

**Task-02**  
Build a multiple linear regression model to **predict car prices** using selected features from the dataset.

- Dataset: `car data.csv`
- Target Variable: `Selling_Price`

---

## 📁 Dataset Overview

- Total Rows: `301`
- Features Used:
  - `Present_Price`
  - `Kms_Driven`
  - `Fuel_Type`
  - `Seller_Type`
  - `Transmission`
  - `Owner`
  - `Car_Age` (Calculated from `Year`)

---

## 🧹 Data Cleaning & Preprocessing

- Removed unnecessary columns: `Car_Name`, `Year`
- Created new feature: `Car_Age = Current Year - Year`
- Converted categorical columns using:
  - `LabelEncoder` and `OneHotEncoding`
- Final selected features after encoding and transformation:
