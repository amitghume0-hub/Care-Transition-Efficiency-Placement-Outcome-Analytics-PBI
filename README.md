# Care-Transition-Efficiency-Placement-Outcome-Analytics


# 🏛 HHS Child Welfare System Flow Analysis

## 📌 **Project Overview**

This project analyzes operational data from the **HHS Child Welfare System** to evaluate system flow balance, backlog accumulation, discharge efficiency, and seasonal pressure trends.

The dataset was initially messy and unstructured. Using **Python (Pandas & NumPy) for data manipulation** and **Power BI for visualization**, raw operational records were transformed into structured, decision-ready insights.

The primary objective was to determine:

- Whether the system is stabilizing or accumulating pressure  
- If discharge rates are sufficient to reduce backlog  
- When seasonal demand peaks  
- How significant the existing inventory burden is  

---

## 🎯 **Business Objective**

Child welfare systems must maintain balance between:

- **📥 Inflow (New Entries)**
- **📤 Outflow (Discharges / Transfers)**
- **⏳ Average Stay Duration**
- **⚖ Operational Capacity**

Without proper monitoring, backlog increases gradually and impacts system efficiency.

This project provides a structured, data-driven evaluation of system performance.

---

## 📊 **Dashboard Highlights**

### **1️⃣ Inflow vs Outflow Summary**

| Metric | Value |
|--------|--------|
| **Total Inflow** | 67K |
| **Total Outflow** | 93K |
| **Net Flow** | -25K |

**Insight:**  
Outflow exceeds inflow overall, indicating improved case processing. However, historical backlog continues to drive high system inventory.

---

### **2️⃣ Seasonal Pattern Analysis**

- Highest inflow observed during **February–May (Q2)**
- Noticeable decline during **October**
- Clear recurring seasonal spikes across years

**Insight:**  
Resource allocation should increase during Q2 peak months to manage operational pressure effectively.

---

### **3️⃣ Quarterly Apprehension Trends**

- Q2 consistently records the highest activity
- 2023–2024 experienced elevated system pressure
- 2025 shows early signs of stabilization

---

### **4️⃣ System Pressure Indicators**

| Metric | Value | Interpretation |
|--------|--------|----------------|
| **CBP Pressure Ratio** | 1.33 | Operating above optimal threshold |
| **Average Discharge** | 173 | Stable discharge volume |
| **Days of Inventory** | 960 | Significant accumulated backlog |
| **Total in HHS Care** | 4.36M | High overall system load |

**Insight:**  
Although net flow is negative (more exits than entries), structural pressure remains due to accumulated inventory.

---

### **5️⃣ Monthly Net Flow Monitoring**

Most months reflect negative net flow; however:

- Backlog reduction is gradual  
- Structural inefficiencies may still exist  
- Historical accumulation remains substantial  

---

## 🔄 **Data Processing Workflow (Python)**

The dataset required extensive transformation before analysis.

### **Steps Performed:**

1. Removed duplicate records  
2. Standardized inconsistent date formats  
3. Handled missing discharge values  
4. Cleaned categorical inconsistencies  
5. Created calculated metrics:
   - **Net Flow**
   - **Monthly Aggregations**
   - **Quarterly Trends**
   - **Pressure Ratio**
   - **Inventory Calculation**
6. Exported cleaned dataset for Power BI modeling  

All manipulation was performed using **Pandas operations and aggregation techniques**.

---

## 📊 **Visualization (Power BI)**

The dashboard includes:

- Executive KPI Summary  
- Inflow vs Outflow Trend  
- Seasonal Pattern Analysis  
- Quarterly Apprehension Trend  
- Net Flow Monitoring  
- Discharge vs Apprehension Comparison  

The design focuses on executive-level monitoring and operational decision support.

---

## 🛠️ **Tools & Technologies**

- **Python (Pandas, NumPy)** — Data Cleaning & Feature Engineering  
- **Power BI Desktop** — Data Modeling & Visualization  
- **Power Query** — BI Layer Transformations  
- **CSV Dataset** — Source Data  

---

## 📂 **Project Structure**

