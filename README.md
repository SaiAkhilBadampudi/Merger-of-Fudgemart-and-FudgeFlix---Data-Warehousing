# 📊 Data Warehouse for FudgeMart & FudgeFlix

This project unifies and aggregates customer review data from two subsidiaries of FudgeMart Inc.: **FudgeMart**, an online consumer goods retailer, and **FudgeFlix**, a movie rental distributor.

The goal was to implement a **Kimball Data Warehouse approach** to create a common data source for business intelligence, enabling insights into customer experience.

---

### ⭐ Key Features

* **Unified Data Source**: Integrates two separate databases into one.
* **Star Schema**: Employs a star schema with a central `FactReviews` table and several dimension tables (`DimCustomers`, `DimProducts`, `DimDate`) to support analytical queries.
* **Business Intelligence**: Generates insights on customer reviews across various dimensions, including product, genre, region, and company as a whole.

---

### 📈 Key Findings

* **Overall Rating**: The average customer rating across both companies is **2.3**.
* **FudgeMart**: Has a slightly higher average rating of **2.49** compared to FudgeFlix's **2.22**.
* **Geographic Insights**: California and New York have the most reviews, while New Jersey has the highest overall average rating.
* **Trend**: Customer reviews show a decreasing trend from 2009 to 2013.

---

### 🔗 Get Started

To analyze the data, business users can:

* Analyze reviews by product, department, or genre.
* Break down reviews by geographical region.
* Compare reviews between FudgeMart and FudgeFlix.
* Track product and title reviews over time.
