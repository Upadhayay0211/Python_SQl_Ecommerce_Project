# 🛒 Ecommerce Business Intelligence Analysis
### *Bridging Data Engineering and Strategic Insights*

## 📌 Project Overview
In the world of online retail, data is the heartbeat of decision-making. This project explores a massive ecommerce dataset to solve real-world business problems. I built a pipeline to ingest raw CSV data into a **MySQL database**, performed complex analytical queries, and used **Python** to visualize trends that impact growth and retention.

**The Goal:** To transform thousands of rows of customer, order, and payment data into a clear story about business health.

---

## ⚙️ Technical Toolkit
* **Database:** MySQL (Relational schema design, complex Joins, Window Functions)
* **Languages:** Python (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
* **Concepts:** ETL (Extract, Transform, Load), Exploratory Data Analysis (EDA), Year-over-Year (YoY) Growth, and Moving Averages.

---

## 🔑 Business Questions Answered
I focused on core pillars of ecommerce health:

1. **Revenue Growth:** Calculated Year-over-Year (YoY) growth and cumulative sales to track the platform's scaling trajectory.
2. **Customer Behavior:** Analyzed the moving average of order values per customer to identify spending patterns.
3. **Operational Efficiency:** Evaluated order count trends per month and identified monthly peaks for inventory planning.
4. **Market Analysis:** Ranked product categories by revenue and calculated their percentage contribution to total sales.
5. **Seller Performance:** Identified and ranked top-performing sellers based on total revenue generated.

---

## 📂 Project Structure
* `Python & SQL Ecommerce Project.ipynb`: The complete end-to-end technical workflow.
* **ETL Phase:** Python script to handle `NaN` values, clean column headers, and dynamically create MySQL tables.
* **Analysis Phase:** Advanced SQL queries utilizing **CTEs (Common Table Expressions)** and **Window Functions** such as `DENSE_RANK` and `LAG`.
* **Visualization Phase:** Visual representations of geographic distribution, seasonal trends, and revenue ranks.

---

## 📈 Key Insights & Findings
* **Growth Spikes:** Identified a massive YoY growth percentage between 2016 and 2017, marking the platform's market entry success.
* **Retention:** Developed a retention rate logic to monitor customers making repeat purchases within 6 months.
* **Top Contributors:** Found that categories like *Bed Table Bath* and *Health Beauty* are the primary revenue drivers.

---

## 🎯 Why This Matters
This project isn't just about writing code; it's about **Business Storytelling**. I demonstrated the ability to:
* Handle the "messy" part of data (ETL and cleaning).
* Write production-level SQL for high-performance analysis.
* Translate technical outputs into visual insights that a Marketing or Operations Manager could use to make a decision.

---

## 🚀 How to Run
1. Ensure you have a local MySQL instance running.
2. Update the database credentials in the notebook connection string.
3. Install dependencies: `pip install pandas mysql-connector-python matplotlib seaborn`.
4. Run the cells in order to process the raw data and generate the report.

---

**Contact:** [Abhishek Upadhayay](mailto:aupadhayay0211@gmail.com)  
