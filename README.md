# Test Environment Inventory Dashboard (Snowflake + AWS + Power BI)

## 📌 Project Overview
This project demonstrates how **Snowflake (cloud data warehouse)** and **AWS cloud services** can be integrated with **Power BI** to analyze **test environment inventory datasets**.  
The dashboard helps monitor:
- Environment utilization
- Resource allocation
- Infrastructure performance
- Cost optimization

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** (for visualization & DAX)
- **Snowflake** (cloud data warehouse for data storage & querying)
- **AWS (S3 + Redshift/EC2)** (data hosting and compute environment)
- **SQL** (for transformations and queries)
- **DAX** (for measures & KPIs)

---

## 📊 Dashboard Features
- **Environment Utilization** – Active vs Idle environments.
- **Inventory Breakdown** – Servers, devices, licenses, and resource categories.
- **Cloud Cost Analysis** – Resource usage cost trends from AWS.
- **Snowflake Queries Integration** – Real-time data loading into Power BI.

---

## 📂 Repository Structure

---

## ⚡ Data Flow (Architecture)
1. **AWS S3** – Stores raw test environment inventory data.  
2. **Snowflake** – Ingests and models the dataset for structured querying.  
3. **Power BI** – Connects to Snowflake (via ODBC/DirectQuery/Import) to build interactive dashboards.  

---

## 📸 Dashboard Preview
![Overview](Screenshots/overview.png)  
![Environment Utilization](Screenshots/environment_utilization.png)  
![Snowflake Query Integration](Screenshots/aws_snowflake_connection.png)  

---

## 🚀 How to Use
1. Download the `.pbix` file from this repo.
2. Open in **Power BI Desktop**.
3. Update the Snowflake credentials in **Data Source Settings**.
4. Refresh the dataset to load live data.
5. Explore the dashboard.

---

## 🔑 Key Insights
- Identified **25% idle environments** across regions.  
- Highlighted **high-cost AWS resources** with low utilization.  
- Helped optimize **test cycle planning and resource allocation**.  

---

## 📧 Contact
Created by **[Pushkar Dhavane](https://github.com/pushkard17)**  
For questions, reach out on GitHub or LinkedIn.

