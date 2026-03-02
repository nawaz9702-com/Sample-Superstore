
# Sample Superstore Data Description

The **Sample Superstore** dataset is a retail sales analytics database sourced from an Excel file, organized as a **dimensional model** with the following structure:

---

## 📌 Core Fact Table

### **Orders_Fact**

Contains **13 columns** capturing transactional data:

* **Identifiers**

  * Row ID
  * Order ID
  * Customer ID
  * Product ID

* **Dates**

  * Order Date
  * Ship Date

* **Location**

  * Postal Code
  * Region ID

* **Metrics**

  * Sales
  * Quantity
  * Discount
  * Profit

* **Shipping**

  * ShipMode ID

---

## 📊 Dimension Tables

### **Customer_Dim** *(3 columns)*

* Customer ID
* Customer Name
* Segment

---

### **Product_Dim** *(4 columns)*

* Product ID
* Category
* Sub-Category
* Product Name

---

### **Location_Dim** *(5 columns)*

* Postal Code
* City
* State
* Region
* Country

---

### **People_Dim** *(3 columns)*

* Region
* Associated People
* Manager Information

---

### **ShipMode_Dim** *(2 columns)*

* ShipMode ID
* Shipping Mode Details

---

### **Returns_Dim** *(2 columns)*

* Return Transaction Information
* Associated Order ID

---

## 📈 Measures & KPIs (44 Total)

Organized into logical folders:

---

### 📦 Aggregates

* Revenue
* Profit
* Quantity Sold
* Orders
* Cost
* Total Discount
* Total Customers
* Returned Amount

---

### 🚀 Performance Metrics

* Delivery Rate
* Return Rate
* Average Delivery Days
* Maximum Delivery Days

---

### 📅 Year-over-Year Cards

Current Year vs Last Year comparisons for:

* Revenue
* Cost
* Profit
* Quantity
* Delivery Days

---

### 👁 View Measures

* Alternative views of core metrics

---
### Screenshots / Demos

![Dashboard Preview](https://github.com/nawaz9702-com/Sample-Superstore/blob/main/Sample%20Superstore.png)
