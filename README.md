# Restaurant-Business-Intelligence-Dashboards.

A comprehensive Business Intelligence solution built to streamline restaurant operations, track financial performance, and monitor kitchen efficiency. This project consolidates raw data from multiple operational Excel files into a centralized, interactive data model tailored for different business stakeholders.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop** (Data Modeling, DAX, Dashboard Design)
* **Power Query** (Data Cleaning, Transformation, and ETL)
* **Excel** (Raw Data Sources)

---

##  Data Pipeline & Architecture
1. **Data Ingestion:** Imported raw operational data from multiple disparate Excel files covering sales, menu items, orders, and payments.
2. **Data Cleaning & Transformation (Power Query):** Handled missing values, standardized date formats, removed duplicates, and prepped tables for analysis.
3. **Data Modeling (Star Schema):** 
   * Built centralized **Fact Tables** for daily transactional metrics and order volumes[cite: 1, 2].
   * Connected relevant dimension tables to establish robust relationship models, ensuring optimal filter propagation.
4. **Calculations & DAX:** Added calculated columns and advanced measures (e.g., Average Order Value, Net Sales Growth %, Settlement Rate, and Outstanding Amounts) to power executive KPIs[cite: 1, 2]

---

##  Dashboard Views & Key Insights
The report is structured into insights across multiple analytical dimensions:
* **Executive Sales Overview:** Tracks total net sales (~₹30.75M), total orders (6,481), Average Order Value (~₹493.56), and monthly sales growth trends[cite: 1].
* **Sales & Category Analysis:** Compares ordered vs. settled amounts, highlighting high-performing categories like Main Course and Breads, along with payment method breakdowns (Cash, UPI, Card)[cite: 1, 2].
* **Order Channel & Operations:** Analyzes hourly order distributions to identify peak dining rush hours (notably between 7 PM and 9 PM) for better staffing and kitchen prep[cite: 1, 2].
* **Product Performance Analysis:** Evaluates top-selling items by quantity and revenue (such as Mineral Water, Kesar Rasmalai, and Aloo Paratha) alongside individual item unit pricing[cite: 1, 2].

---

##  Dashboard Preview
*(Explore the uploaded R_K_Restaurant _Dashboards PDF in this repository for a complete visual walkthrough of all dashboard pages).*

