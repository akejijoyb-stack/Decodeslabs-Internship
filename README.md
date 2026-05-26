# Decodeslabs-Internship
Internships Projects
# Data Cleaning Project – Week 1

## 📊 Project Overview
This project focused on cleaning and preparing a raw e-commerce dataset for analysis. The objective was to improve data quality by identifying missing values, removing inconsistencies, validating data formats, and standardizing text fields.

---

## 🎯 Objectives
- Identify and handle missing values  
- Detect and confirm the absence of duplicate records  
- Validate and correct data formats  
- Standardize text entries for consistency  
- Prepare the dataset for future analysis  

---

## 📁 Dataset Information
- **Dataset Type:** E-Commerce Sales Data  
- **Total Records:** 1,200  
- **Total Columns:** 14  

---

<img width="1365" height="724" alt="Before cleaning" src="https://github.com/user-attachments/assets/26baf549-1f2d-4f9b-8acc-1c1cd5e22f82" />
## 🛠️ Tools Used
- Microsoft Excel  
- Power Query (Data Cleaning Techniques)  

---

## 🧹 Data Cleaning Process

### 1. Missing Value Analysis
A full scan of the dataset was conducted to identify missing or null values.

**Findings:**
- `CouponCode` column contained **309 missing values**
- All other columns had complete records

**Action Taken:**
- Replaced missing values in `CouponCode` with **"No Coupon"** to maintain consistency and preserve data integrity
<img width="1365" height="729" alt="Power Query" src="https://github.com/user-attachments/assets/229a98d3-48d3-4181-8459-4fb7fa62fd3f" />

---

### 2. Duplicate Check
The dataset was checked for duplicate records.

**Findings:**
- No duplicate rows were identified  

**Action Taken:**
- No removal was required  
<img width="1365" height="722" alt="Duplicate check" src="https://github.com/user-attachments/assets/8196cd8d-6264-41bd-b285-ee605a3aabf3" />

---

### 3. Data Type Validation
All columns were reviewed to ensure correct formatting and data consistency.

| Column Type      | Status        |
|------------------|--------------|
| Date Fields      | Verified      |
| Numeric Fields   | Verified      |
| Text Fields      | Verified      |

**Action Taken:**
- Confirmed appropriate formatting across all fields

---

### 4. Text Standardization
Text-based columns were reviewed for consistency and uniformity.

**Actions Taken:**
- Standardized text casing where necessary  
- Removed leading and trailing spaces  
- Preserved unique identifiers such as:
  - Order ID  
  - Customer ID  
  - Tracking Number  

---

## 📌 Summary of Cleaning Activities

| Task                         | Status |
|------------------------------|--------|
| Missing Values Identified    | ✅ Done |
| Missing Values Treated       | ✅ Done |
| Duplicate Records Checked    | ✅ Done |
| Data Formats Validated       | ✅ Done |
| Text Standardization Applied | ✅ Done |
| Dataset Prepared for Analysis| ✅ Done |
<img width="1365" height="726" alt="Project 1" src="https://github.com/user-attachments/assets/91b57dbe-8312-4e07-8f93-498da6e175f3" />

---

## 📈 Key Learning Outcomes
Through this project, I gained hands-on experience in:
- Data cleaning and preprocessing
- Handling missing values effectively
- Ensuring data consistency and accuracy
- Data validation techniques
- Preparing datasets for analytical modeling

---

## ✅ Conclusion
The dataset was successfully cleaned and prepared for analysis. All identified data quality issues were addressed, resulting in a structured, consistent, and analysis-ready dataset.
