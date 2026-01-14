# SQL Analytics & Exploratory Data Analysis

## 📘 Project Overview

This project demonstrates an end-to-end **SQL analytics workflow** combining guided business-driven queries with open-ended exploratory analysis. Using real-world–style relational databases, the project highlights the ability to translate business questions into SQL, extract insights, and communicate results through clear visualizations and written analysis.

The work is divided into two parts:

* **Part 1:** Structured SQL analysis for a wholesale product company
* **Part 2:** Independent exploratory analysis using an IMDB movie dataset

---

## 🎯 Key Skills Demonstrated

* Translating business questions into SQL queries
* Writing complex SQL using `JOIN`, `GROUP BY`, `HAVING`, subqueries, and aggregates
* Performing exploratory data analysis (EDA) with SQL + Pandas
* Creating effective visualizations with Matplotlib and Seaborn
* Interpreting results and communicating insights to non-technical stakeholders

---

## 🧩 Part 1: Guided SQL Analysis (Wholesale Business Case)

### 🏢 Business Context

The company sells wholesale miniature models (cars, planes, motorcycles, etc.) and wants insights into:

* Customer segmentation for marketing campaigns
* Credit policy optimization
* Inventory allocation
* Product demand and portfolio performance
* Employee office structure to support remote work decisions

---

### 📊 Analysis Highlights

**Customer Targeting**

* Identified high-credit customers in California for premium product promotions
* Selected international customers for a global collectibles campaign

**Credit Policy & Inventory Planning**

* Computed average credit limits by U.S. state
* Visualized state-level differences to support inventory prioritization and credit strategy

**Top Customers**

* Ranked top 10 customers by lifetime payment value
* Created visualizations to support customer appreciation initiatives

**Product & Inventory Analysis**

* Identified products frequently purchased in large quantities per customer
* Analyzed product line diversity vs. total demand
* Used scatter plots to explore whether more products lead to more orders

**Workforce & Operations**

* Used subqueries to identify offices with fewer than five employees
* Retrieved employee and supervisor data to support hybrid/remote planning

---

## 🛠 Tools & Technologies (Part 1)

* SQL (SQLite)
* Pandas
* Matplotlib
* Seaborn

---

## 🎬 Part 2: Exploratory SQL Analysis (IMDB Movies Dataset)

### 📂 Dataset Overview

* Source: IMDB
* Time range: **2010–2019**
* Data includes movie metadata, genres, runtimes, ratings, and vote counts

---

### 🔍 Initial Exploration

* Filtered movies to valid release years
* Examined null values, duplicates, and outliers
* Identified runtime anomalies and duplicate title/year combinations
* Extracted and normalized genre information

---

### 📈 Key Insight: Genre vs. Ratings

**Business Question:**

> *How do movie genres influence average audience ratings (2010–2019)?*

**Findings:**

* Documentary, Drama, Biography, and Animation genres achieve the highest average ratings
* Action, Horror, and Thriller tend to receive lower average ratings despite popularity
* Comedy sits near the middle, reflecting broad appeal with mixed critical reception

**Business Insight:**
While blockbuster genres may drive box office revenue, higher-rated genres contribute more to long-term reputation and critical acclaim. Studios may benefit from balancing commercial appeal with high-rating genres to optimize both profitability and brand value.

---

### 📊 Visualization

* Created genre-level rating visualizations to clearly compare audience perception across categories

---

### 🧹 Data Quality Observations

Potential data cleaning steps identified:

* Handling duplicate movie titles across years
* Addressing extreme runtime outliers
* Normalizing multi-genre records
* Ensuring no target leakage in rating-based analyses

---

## 📌 Project Takeaways

* Demonstrates strong SQL fundamentals applied to real business scenarios
* Shows ability to move from guided analysis to independent exploration
* Emphasizes both technical execution and business interpretation
* Highlights effective communication through visuals and written insights

---

## 📁 Repository Structure

```
├── data.sqlite
├── im.db
├── notebooks/
│   ├── guided_sql_analysis.ipynb
│   └── imdb_exploratory_analysis.ipynb
├── visuals/
│   └── avg_rating_by_genre.png
└── README.md
```

---

## 🚀 Future Improvements

* Deeper modeling of genre popularity vs. commercial success
* Time-series trends in ratings and production volume
* Integration with dashboarding tools (Tableau / Streamlit)

---

## 👤 Author

**Faheem**
Data Analyst | SQL | Python | Data Visualization



