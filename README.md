📌 Microsoft Fabric LMS Analytics Project
This project builds an end-to-end data pipeline in Microsoft Fabric for analyzing Learning Management System (LMS) data. It processes student demographics, course enrollments, learning preferences, and performance metrics using Microsoft Fabric components such as OneLake, Data Factory, Synapse Analytics, and Power BI. Additionally, it includes CI/CD automation for seamless deployment and updates.

📂 Project Structure
![image](https://github.com/user-attachments/assets/a37c2001-f387-44da-a73d-7ff52bd5feaf)

🚀 Features
✅ Data Pipeline: Ingests, processes, and transforms LMS data from OneLake
✅ Lakehouse & Data Warehouse: Stores structured, semi-structured, and unstructured data for analysis
✅ CI/CD Integration: Automates deployment of Fabric workspaces, pipelines, and Power BI reports
✅ Power BI Dashboards: Visualizes student performance, learning trends, and completion rates
✅ Security & Access Control: Implements RBAC, OneLake access policies, and Row-Level Security (RLS)

📊 Data Processing Flow
Raw → Landing: Ingests raw data from LMS into OneLake

Landing → Bronze: Cleans and stores structured data in the Bronze Lakehouse

Bronze → Silver: Applies data transformations for analytics-ready data

Silver → Gold: Aggregates final data with business logic in Gold Lakehouse

End-to-End Orchestration: Automates scheduling using Data Factory Pipelines

📌 Pipeline Overview:
![image](https://github.com/user-attachments/assets/db9ea491-4550-4d92-88f1-82b3ded81937)

📌 Power BI Dashboard Preview:
![image](https://github.com/user-attachments/assets/56a9630a-3c35-41f2-9da8-74ffab2351e0)

🛠️ Tech Stack
🔹 Microsoft Fabric (OneLake, Data Factory, Synapse Analytics, Power BI)
🔹 Azure Data Services (ADLS, Data Factory)
🔹 Spark & SQL (Data Transformation)
🔹 GitHub Actions / Azure DevOps (CI/CD Automation)

🔧 Setup Instructions
Pre-requisites
✔ Azure Account with Fabric-enabled workspace
✔ Basic knowledge of SQL & PySpark
