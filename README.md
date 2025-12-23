# 📊 DAX Depo — Advanced DAX Calculations in Power BI  

> **📘 Project Type:** Academic  
> **🛠 Tool Used:** Microsoft Power BI  
> **🎯 Focus Area:** Advanced DAX, Filter Context, Time Intelligence  
> **📐 Visual Constraint:** Matrix visuals only (as per instructions)

---

## 🧠 Project Overview  

**DAX Depo** is a logic-driven Power BI project designed to demonstrate a strong understanding of **advanced DAX concepts** without relying on charts or slicers.

All insights are generated **purely through DAX calculations** and displayed **exclusively using Matrix visuals**, strictly following the given project constraints.

### 🔍 Project Focus
- Sales & Returns data modeling  
- Advanced DAX calculations  
- Filter context behavior  
- Time intelligence analysis  

---

## 🗂 Dataset Details  

The project follows a **Star Schema** data model with the following tables:

| Table Name | Type | Description |
|-----------|------|-------------|
| `Sales_Fact` | Fact Table | Sales transactions |
| `Returns_Fact` | Fact Table | Returned items |
| `Customer_Dim` | Dimension | Customer attributes |
| `Product_Dim` | Dimension | Product details |
| `Date_Dim` | Dimension | Calendar table |
| `Region_Dim` | Dimension | Sales regions |

📥 **Dataset File:**  
👉 `DAX_Depo_Sample_Datasets.xlsx`

---

## 🧮 DAX Concepts Covered  

This project implements **all required and advanced DAX functions**.

### 🔹 Aggregation & Statistics
- `SUM`, `AVERAGE`, `MAX`
- `COUNTX`, `DISTINCTCOUNT`

### 🔹 Logical & Text Functions
- `IF`, `AND`, `OR`, `SWITCH`
- `CONCATENATE`, `LEFT`, `UPPER`

### 🔹 Filter Context & Iterators
- `ALL`, `FILTER`, `CALCULATE`
- `SUMX`, `AVERAGEX`

### 🔹 Relationships
- `RELATED()`  
  *(Used to fetch dimension attributes into fact tables)*

### 🔹 Time Intelligence
- `DATESBETWEEN`
- `DATESINPERIOD`
- `TOTALYTD`
- `SAMEPERIODLASTYEAR`
- Running totals & rolling period analysis

---

## 📐 Matrix Visual Analysis (Final Output)  

✔ Only **Matrix visuals** used  
✔ No charts, slicers, or cards  

📷 **Matrix Visual Screenshot:**  

![DAX Depo Matrix Visuals](Visuals.png)

---

## 📌 Matrix Breakdown  

### 🟦 1. Core Sales KPIs  
Metrics displayed by **Region**:
- Total Sales  
- Total Cost  
- Total Profit  
- Return Rate (%)  
- Average Sale per Transaction  

🎯 *Purpose:* Business performance evaluation  

---

### 🟦 2. Filter Context Comparison  
Comparison of:
- Normal Total Sales  
- Total Sales using `ALL()`  
- Total Sales using `FILTER()` + `CALCULATE()`  

🎯 *Purpose:* Understanding filter context manipulation  

---

### 🟦 3. Time Intelligence Analysis  
Includes:
- Year → Month hierarchy  
- Last 3 Months Sales  
- Running Total  
- Year-to-Date (YTD) Sales  

🎯 *Purpose:* Time-based trend analysis  

---

## 📁 Project Files Included  

| File Name | Description |
|----------|-------------|
| `DAX Depo.pbix` | Complete Power BI project |
| `DAX_Depo_Sample_Datasets.xlsx` | Source dataset |
| `Visuals.png` | Matrix visuals screenshot |

---

## ✅ Key Highlights  

✔ Matrix visuals only (strict compliance)  
✔ Clean Star Schema data model  
✔ Dedicated Measure Table for DAX  
✔ Real-world DAX use cases  
✔ Academic & interview-ready project  

---

## 🏁 Conclusion  

This project demonstrates **advanced DAX proficiency**, focusing on **logic, filter context, and time intelligence** rather than visual complexity.

It fully aligns with the project instructions and reflects **industry-standard Power BI practices**.

---

## 📌 Learning Outcomes  

Through **DAX Depo**, I gained hands-on experience in:

- Designing a clean Star Schema  
- Writing advanced DAX measures  
- Understanding filter context & context transition  
- Applying time intelligence functions  
- Presenting insights using **Matrix visuals only**

🚀 This project strengthened my DAX fundamentals and improved my confidence in building logic-driven Power BI reports.
