# 🏛️ SQL Server Data Warehouse Project

A modern Data Warehouse built on Microsoft SQL Server that turns raw CRM and ERP data into clean, business-ready insights. It delivers a complete ETL pipeline with batch processing and analytics, organized using the Medallion Architecture (Bronze, Silver, Gold).

<img width="742" height="574" alt="data_architecture" src="https://github.com/user-attachments/assets/3c2ff7ce-46e0-4f94-83c2-e8f572af6647" />


The implementation is inspired by Baraa Khatib Salkini's tutorials on data warehousing.

## 🗂️ Project Structure

### 🥉 Bronze Layer
- Extracted and loaded CRM and ERP data from CSV files into staging tables.
- Implemented full-load batch processing for initial ingestion.

### 🥈 Silver Layer
- Built the Integration Model with data cleansing, transformation, and normalization.
- Designed reusable stored procedures for data transformations.
- Established a data catalog for structured metadata and improved discoverability.

### 🥇 Gold Layer
- Modeled business-ready data into a Star Schema for reporting and analytics.
- Optimized for performance using views, indexing strategies, and partitioning.

  <img width="848" height="481" alt="data_flow" src="https://github.com/user-attachments/assets/44095154-a48b-40be-b04e-197a1b46b985" />


## 🛠️ Technologies Used
- 🗄️ **Database:** Microsoft SQL Server
- 🔄 **ETL Tools:** T-SQL scripts, SQL Server Integration Services (SSIS)
- 📄 **Data Sources:** CSV files
- 📊 **Analytics:** SQL-based reports and dashboards

<img width="822" height="551" alt="integration_model" src="https://github.com/user-attachments/assets/cc4f9554-2151-488e-b48f-d3ae0a2a0173" />

- The Gold Layer is a star schema with one fact table and two dimension tables, linked through surrogate keys.

<img width="752" height="453" alt="data_model" src="https://github.com/user-attachments/assets/1fc5abe3-d7fa-4a7d-934e-aabeb1a703f4" />
 
## 🎯 Objectives
- Implement a structured ETL pipeline using T-SQL and SSIS.
- Support batch processing with full-load strategies for raw data ingestion.
- Apply the Medallion Architecture (Bronze, Silver, Gold) for layered data processing.
- Use stored procedures for modular and reusable ETL logic.
- Maintain a data catalog for clear lineage and data definitions.
- Design a Star Schema for business intelligence and analytics.
- Optimize performance with views, indexes, and query tuning.
- Provide a scalable and extensible data warehouse model.

## 📚 Resources
- 🎥 **YouTube Channel:** [Data with Baraa](https://www.youtube.com/@DataWithBaraa)
- 📺 **Tutorial Video:** SQL Data Warehouse from Scratch | Full Hands-On Data Engineering Project
---

## License 

This project is licensed under the [MIT License] (LICENSE).
