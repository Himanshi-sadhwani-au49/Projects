# Enterprise Azure Data Engineering Pipeline with Microsoft Fabric ✨

This project demonstrates the implementation of an end-to-end Data Engineering solution using Azure cloud services and Microsoft Fabric. The solution processes, transforms, and delivers enterprise data for analytics and Business Intelligence use cases by leveraging Azure Data Factory, Azure Databricks, Azure Synapse Analytics, ADLS Gen2, Microsoft Fabric, and Power BI.

The project uses the **AdventureWorks dataset** as the primary data source and follows the **Medallion Architecture (Bronze → Silver → Gold)** approach to build a scalable modern Lakehouse solution.

---

# 📌 Architecture Overview

The solution simulates a real-world enterprise data platform capable of handling scalable data ingestion, transformation, warehousing, and reporting workflows.

![project](https://github.com/user-attachments/assets/7c51260a-236e-43ae-a965-91508684014c)

---

# ⚙️ Azure Services Used

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS Gen2)
- Azure Databricks
- Azure Synapse Analytics
- Microsoft Fabric
- OneLake
- Power BI
- Delta Lake
- PySpark

---

# 🏗️ Solution Architecture

```text
Source Data (GitHub / APIs)
        ↓
Azure Data Factory (ADF)
        ↓
ADLS Gen2 Bronze Layer
        ↓
Azure Databricks + PySpark
        ↓
Silver Layer (Parquet/Delta)
        ↓
Azure Synapse Analytics
        ↓
Gold Layer
        ↓
Microsoft Fabric / Power BI
