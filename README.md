# decodelabs_Data-cleaning
# 🧹 DecodeLabs Project 1 – Data Cleaning

## 📌 Project Overview

This project focuses on **data cleaning and preprocessing** of an e-commerce order dataset using Microsoft Excel.

The main purpose of this project was to transform raw data into a cleaner and more structured dataset that can be used reliably for further analysis and visualization.

This project was completed as part of **DecodeLabs Project 1**.

---

## 🎯 Objectives

The main objectives of this project were:

* Understand the structure of the raw dataset
* Identify data quality issues
* Clean and organize the dataset
* Check for missing values
* Identify duplicate records
* Verify data types and formats
* Standardize the dataset
* Validate calculated fields
* Prepare the final dataset for Exploratory Data Analysis (EDA)

---

## 📂 Dataset

The dataset contains **1,200 e-commerce order records** and **14 columns**.

### Dataset Columns

| Column          | Description                                         |
| --------------- | --------------------------------------------------- |
| OrderID         | Unique identification number for each order         |
| Date            | Date on which the order was placed                  |
| CustomerID      | Unique customer identification                      |
| Product         | Product purchased                                   |
| Quantity        | Number of units purchased                           |
| UnitPrice       | Price of one unit                                   |
| ShippingAddress | Customer shipping address                           |
| PaymentMethod   | Payment method used                                 |
| OrderStatus     | Current status of the order                         |
| TrackingNumber  | Shipment tracking number                            |
| ItemsInCart     | Number of items in the customer's cart              |
| CouponCode      | Coupon or discount code used                        |
| ReferralSource  | Source through which the customer reached the store |
| TotalPrice      | Total value of the order                            |

---

## 🛠️ Tools Used

* **Microsoft Excel**
* Data Cleaning
* Data Validation
* Duplicate Detection
* Data Formatting
* Formula Validation
* Basic Data Quality Checks

---

## 🧹 Data Cleaning Process

### 1. Data Inspection

The dataset was first inspected to understand:

* Number of rows and columns
* Column names
* Data types
* Categorical variables
* Numerical variables
* Date fields
* Potential data-quality issues

---

### 2. Missing Value Check

The dataset was checked for missing or blank values.

Special attention was given to important fields such as:

* OrderID
* CustomerID
* Product
* Quantity
* UnitPrice
* OrderStatus
* TotalPrice

---

### 3. Duplicate Check

The dataset was checked for duplicate records.

Order IDs and complete records were examined to ensure that duplicate entries would not affect further analysis.

---

### 4. Data Formatting

Different fields were formatted appropriately.

Examples include:

* Dates formatted as date values
* Prices formatted as numerical/currency values
* Quantities stored as numerical values
* Categorical fields standardized
* IDs and tracking numbers maintained as identifiers

---

### 5. Data Validation

The values of important columns were checked for consistency.

Examples:

* Quantity should contain valid numerical values.
* UnitPrice should contain positive values.
* TotalPrice should correspond to the order quantity and unit price.
* OrderStatus should contain valid categories.
* PaymentMethod should contain consistent categories.

---

### 6. Total Price Validation

The relationship between quantity, unit price, and total price was checked.

The expected calculation is:

**TotalPrice = Quantity × UnitPrice**

This helps ensure that the calculated order values are consistent with the underlying data.

---

## 📊 Final Dataset

After the cleaning and validation process, the dataset was organized into a structured format containing:

* **1,200 records**
* **14 variables**

The cleaned dataset can be used as the foundation for further **Exploratory Data Analysis (EDA)** and visualization.
---

## 💡 Key Learning Outcomes

Through this project, I learned:

* How to inspect a raw dataset
* How to identify data-quality problems
* How to clean and organize Excel datasets
* How to check duplicate records
* How to validate numerical and categorical data
* How to work with dates and numerical values
* How to prepare datasets for EDA
* The importance of data quality before performing analysis

---

## 🔗 Next Step

The cleaned dataset serves as the foundation for **DecodeLabs Project 2 – Exploratory Data Analysis**, where the data can be analyzed using statistics, pivot tables, charts, correlations, and business insights.

---

## 👩‍💻 Project Information

**Project:** DecodeLabs Project 1 – Data Cleaning
**Tool:** Microsoft Excel
**Dataset:** E-commerce Orders
**Records:** 1,200
**Columns:** 14
**Focus:** Data Cleaning & Preprocessing
