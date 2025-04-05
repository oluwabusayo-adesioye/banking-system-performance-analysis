# Banking-System-Performance-Analysis
##  Project Overview  
This project evaluates the performance of GoldmanStanley’s online banking system by analyzing transaction data collected during simulated load testing. The goal is to assess system speed, efficiency, and failure/success rates and determine whether the platform meets its performance promises.

Using **Excel Macros, Pivot Tables, and Dashboards**, key insights into **response times, throughput, and error rates** were uncovered. The findings help assess where the system excels and where improvements are needed.  

---

## Dataset Description  
The dataset contains records of banking transactions processed under simulated conditions. It includes:    
- **Response times**  
- **Throughput (transactions per second)**  
- **Error percentages**
  
---

 ## Objectives & Key Questions  
**Speed & Efficiency**: How fast does the system respond? Is it within acceptable thresholds?  
**Error Analysis**: How often do transactions fail? Under what conditions?  
**Scalability**: How does system performance change with increased load?  
**Throughput**: Is the system processing enough transactions per second? 

---

## Approach  
**Data Cleaning & Preparation**: Merged multiple sheets using **Excel Macros**.  
**Feature Engineering**: Created calculated columns for **response time classification, error detection, and throughput calculations**.  
**Data Analysis**: Used **Pivot Tables** to identify trends in response times, failures, and system efficiency.  
**Dashboard Visualization**: Designed an **Excel Dashboard** for intuitive data representation.  

---

## Key Insights & Recommendations  
**Average system response time**: `6949 milliseconds` which is above the threshold. 

**System error rate spikes** when transaction loads exceed `70 transactions/second`.  

**Throughput stagnates** significantly beyond `10 transactions`, indicating scalability issues. 

**Recommendation**: Optimize system performance by improving processing power and load balancing. 

---

## 📁 Files in This Repository  
`System_Performance_Testing_Analysis.xlsx` → Processed dataset, Pivot Tables, and Dashboard.

`System_Performance_Testing_Analysis.xlsm` → Processed dataset, Pivot Tables, and Dashboard.

`Problem_Statement.docx` → Project objectives and key questions.  

`Insights_and_Recommendations.docx` → Findings and suggestions for system improvement.  

---

## How to Use This Project  
**Download** `System_Performance_Testing_Analysis.xlsx` and explore the **Pivot Tables & Dashboard**.  
**Review** `Insights_and_Recommendations.docx` for a detailed breakdown of system performance.  
**Modify** the Excel file to test different performance thresholds and scenarios.  

---

## Technologies Used  
**Microsoft Excel** (Macros, Pivot Tables, Dashboards)  
**Power Query** (Data Cleaning & Transformation)  
**Data Analysis & Visualization**  

---

## Author  
👤 **[Oluwabusayo Adesioye]**  
📧 [temiloluwaadesioye@gmail.com]  
🔗 [[LinkedIn](https://www.linkedin.com/in/oluwabusayo-adesioye/)]  

---

**Feel free to fork this repo, suggest improvements, or reach out for collaborations!**
