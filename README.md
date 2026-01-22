# powerbi-sales-data-append
Power BI project demonstrating how to import and append monthly CSV files into a single dataset.

# Power BI – Importing & Appending Monthly Sales Data

## 📊 Project Overview
This project demonstrates how to import and append multiple monthly CSV files in **Power BI** to create a single consolidated dataset for analysis.

The data represents order-level information from an online food delivery company (Somato). Each CSV file contains data for a different month but follows the same schema.

---

## 📂 Dataset Description
The project uses three monthly CSV files:

- Sales_January.csv  
- Sales_February.csv  
- Sales_March.csv  

Each file contains the following columns:
- order_id  
- orderDate  
- customer_id  
- Resturant_ID  
- Fooditem  
- quantity  
- deliver_status  
- payment_method  

---

## 🎯 Objective
To combine all monthly sales data into a **single dataset** for **Quarter 1 (January–March)** analysis using Power BI.

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- Power Query Editor  
- CSV files  

---

## 🔄 Process Followed

### 1. Data Import
- Opened **Power BI Desktop**
- Selected **Get Data → Folder**
- Chose the folder containing all monthly CSV files

---

### 2. Combining Files
- Used **Combine & Transform Data**
- Power BI automatically:
  - Detected identical file structure
  - Appended all CSV files row-wise into one table
  - Applied the same transformations to all files

---

### 3. Data Validation
- Verified column names and data types
- Ensured:
  - `orderDate` is in Date format
  - `quantity` is in Whole Number format

---

### 4. Load Data
- Clicked **Close & Apply**
- Loaded the consolidated dataset into the Power BI data model

---

## ✅ Final Output
- A single combined dataset containing sales data for:
  - January
  - February
  - March
- Ready for:
  - Quarterly sales analysis
  - Order trend reporting
  - Delivery status and payment method insights

---

## 📁 Repository Structure

---

## 📝 Key Learnings
- Using **Get Data → Folder** is an efficient way to handle recurring monthly data
- Power Query automatically appends files with identical schemas
- This approach is scalable for future monthly data additions

---

## 📌 Notes
- No DAX calculations were required for this task
- The focus of this project is data ingestion and consolidation

---



