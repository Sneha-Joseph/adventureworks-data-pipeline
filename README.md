# AdventureWorks End-to-End Data Engineering Pipeline 🚀

## 📌 Project Overview
This project demonstrates an end-to-end **Azure Data Engineering pipeline** to process and analyze **AdventureWorks sales data** using modern cloud technologies.

## 🏗 Architecture
![Pipeline Architecture](images/pipeline.png)

**Steps:**
1. **Data Ingestion (Bronze Layer)**  
   - Azure Data Factory with Managed Identity to pull **10+ datasets** from GitHub.
   - Stored raw data in Azure Data Lake (Bronze).

2. **Data Processing (Silver Layer)**  
   - Azure Databricks (PySpark) scripts for cleaning, transformation, and joins.
   - Processed **1M+ rows** into Parquet format, reducing processing time by **40%**.

3. **Data Analytics (Gold Layer)**  
   - Azure Synapse Analytics with `OPENROWSET` to query Parquet files from Silver layer.
   - Created **7 analytical Gold views** for BI.

4. **Visualization**  
   - Power BI dashboard with **15+ interactive visuals** showing sales trends, customer demographics, and product performance.

---

## 📊 Tech Stack
- **Cloud:** Azure Data Factory, Azure Data Lake, Azure Synapse Analytics
- **Processing:** Azure Databricks, PySpark
- **Storage Format:** Parquet
- **Visualization:** Power BI
- **Security:** Managed Identity
- **Version Control:** GitHub

---

## 📈 Key Outcomes
- Processed over **100K+ sales records**.
- Reduced query response time to **sub-second performance** in Synapse.
- Delivered an **interactive dashboard** improving data-driven decision-making.

---

## 📷 Screenshots
**Pipeline:**
![Pipeline](images/pipeline.png)

**Power BI Dashboard:**
![Dashboard](images/dashboard.png)

---

## 📂 Repository Structure
