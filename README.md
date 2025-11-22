# 🛒 Walmart Sales Dashboard

An interactive Power BI dashboard analyzing **Walmart's weekly sales**, **temperature trends**, **holiday impact**, and **store-level performance**.  
The dashboard provides clear insights into revenue distribution across seasons, stores, and years using dynamic filters.

---

## 📊 Dashboard Highlights

### **Key KPIs**
- **$301M – $275M** Weekly Sales (Top Stores Shown)  
- **6435** — Total Sales Count  
- **450** — Holiday Flag Count  
- **6435** — Unemployment Count  

### **Included Visuals**
- 📈 **Weekly Sales by Store**  
- 🌡 **Temperature Count by Month**  
- 📅 **Year & Month Smart Filters**  
- ⭐ **Holiday Impact Metrics**  
- 📊 **Store-Level Sales Comparison (Bar Chart)**  
- 🎛 Interactive slicers for **Year**, **Month**, and **Store ID**

---

## 🗂 Files in This Repository

| File | Description |
|------|-------------|
| `walmart_sales.pbix` | Power BI dashboard |
| `Walmart_Sales.csv` | Source dataset used for the analysis |
| `Preview.png` | Dashboard screenshot preview |
| `README.md` | Project documentation |

---

## 🧠 What We Did in This Project

### **1️⃣ Data Loading**
- Imported `Walmart_Sales.csv` into Power BI  
- Verified data quality and ensured consistent formatting  
- Prepared fields: Temperature, Weekly_Sales, Holiday_Flag, Unemployment, Store ID, Date

### **2️⃣ Data Cleaning & Modeling**
- Converted date column to Date type  
- Extracted:
  - **Month**
  - **Year**
  - **Week**
- Created measures for:
  - Total Sales  
  - Weekly Sales  
  - Holiday Flag counts  
- Built a **Calendar Table** to allow time-intelligence filters

### **3️⃣ Dashboard Construction**
Built a polished Walmart-themed dashboard including:

- 💳 KPI Cards with formatted values  
- 📈 Line chart for **Temperature Count by Month**  
- 📊 Clustered Bar chart for **Weekly Sales by Store**  
- 🗂 Month & Year slicers for interactive filtering  
- 🟦 Clean blue theme reflecting Walmart brand identity  

### **4️⃣ Insights Identified**
From the analysis:

- Certain stores consistently outperform others (Store 4, Store 14, Store 20, etc.)  
- Temperature appears to influence shopping cycles across months  
- Holiday periods show spikes in sales  
- Weekly sales vary significantly from store to store  
- Unemployment & holiday flag columns can help in deeper predictive modeling  

---

## 🧩 Tools & Technologies Used
- **Power BI Desktop**  
- **Excel / CSV**  
- **DAX (Time Intelligence & Calculated Measures)**  
- **Data Modeling Techniques**

---

## 🖼 Dashboard Preview
Use the included screenshot: `Preview.png`

![Project Preview](Preview.png)


---

## 🚀 Next Steps
Potential enhancements:
- Build a forecasting model for next year's sales  
- Add Profit & Margin KPIs  
- Add drill-through pages for each store  
- Add What-If analyses for temperature fluctuations  
- Enhance the dashboard with AI Insights (Power BI Premium)

---

## 📘 Repository Description 
> *A professional Walmart Sales Dashboard built using Power BI, analyzing weekly sales, temperature trends, holiday impact, and store-level behavior. Perfect for portfolio use and showcasing BI skills.*

---

## 🎯 Summary
This project delivers a complete Walmart Sales Analysis dashboard with rich interactivity and data-driven insights.  
Perfect for operational monitoring, portfolio demonstration, or business performance tracking.





