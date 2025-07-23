# Uber Data Analytics Project 🚖📊

This project performs end-to-end data analytics on Uber trip data using modern cloud and data engineering tools. The pipeline ingests, transforms, analyzes, and visualizes large-scale trip records to derive insights into ridership behavior, revenue trends, and operational efficiency.

## 🚀 Features

- ✅ Raw data ingestion and processing via **GCP Storage** and **Compute Engine**
- 🔁 ETL pipeline orchestration using **Mage (open-source Data Pipeline Tool)**
- 🧠 Data transformation and analysis with **Python** and **BigQuery**
- 📊 Interactive dashboard creation with **Looker Studio**
- ⚡ Scalable architecture capable of handling 1M+ trip records
- 📈 Insights on Vendor performance, fare patterns, tip behavior, etc.

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

## 📊 Sample Insights

- **VendorID 2** generated **15% higher average fare** than VendorID 1.
- **Credit Card users** tipped **23% more** on average than other payment methods.
- **Evening pickups (5–8 PM)** had the **highest ride frequency** in downtown zones.

---

Here is the project: https://lookerstudio.google.com/reporting/e4ca3c55-fae0-420e-ae22-b5b1119ec387
