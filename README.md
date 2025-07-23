# Uber Data Analytics Project 🚖📊

This project performs end-to-end data analytics on Uber trip data using modern cloud and data engineering tools. The pipeline ingests, transforms, analyzes, and visualizes large-scale trip records to derive insights into ridership behavior, revenue trends, and operational efficiency.

---

## 🚀 Project Highlights

- 🛠️ **Designed and deployed** a cloud-based ETL pipeline to ingest, transform, and analyze **100K+ Uber trip records** using GCP Storage, Python, Mage, and BigQuery — enabling scalable data processing in minutes.
- 📊 **Created dynamic dashboards** in Looker Studio to uncover trends in **trip volume**, **peak hours**, and **payment behavior**, supporting data-driven decisions with real-time insights.

---

## 🛠️ Technologies Used

| Tool            | Purpose                                  |
|-----------------|------------------------------------------|
| GCP Storage     | Stores raw CSV data                      |
| Compute Engine  | Hosts Mage instance and processing scripts |
| Mage            | Builds and runs ETL pipelines            |
| Python          | Data cleaning and transformation         |
| BigQuery        | Querying and aggregating large datasets  |
| Looker Studio   | Data visualization and dashboarding      |

---

## 🧱 Architecture

1. **Data Ingestion**  
   Upload raw Uber data (CSV) to **GCP Storage**.

2. **Data Processing**  
   Use **Mage pipelines** on a **GCP Compute Instance** to:
   - Clean and normalize the data using **Python**
   - Load cleaned data into **BigQuery**

3. **Analytics**  
   Write SQL queries in **BigQuery** to analyze:
   - Fare distribution by Vendor ID
   - Average tips by payment method
   - Pickup patterns by time and location

4. **Visualization**  
   Connect BigQuery to **Looker Studio** to create:
   - Geographic maps
   - Revenue trend charts
   - Behavioral dashboards

---


Here is the project: https://lookerstudio.google.com/reporting/e4ca3c55-fae0-420e-ae22-b5b1119ec387
