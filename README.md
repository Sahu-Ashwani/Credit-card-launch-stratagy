<h1>💳 Data-Driven Launch Strategy for Credit Card</h1>

## 📘 Project Overview

This project presents a **complete end-to-end strategy** for launching a new credit card product — from analyzing user behavior to validating business impact through **A/B testing and data-driven experimentation**.

The work was executed in **two structured phases:**

### 🧩 Phase 1 – Insight-Driven Design
- Analyzed millions of transaction logs to uncover **spending habits, usage gaps, and engagement drivers**.  
- These insights shaped the **product proposition** and **user experience**, aimed at increasing **daily card usage** and **customer retention**.

### 🧪 Phase 2 – Experimentation & Validation
- Designed and executed a **controlled A/B test** using a **two-sample z-test** to evaluate the impact on real users.  
- Results indicated a **2–11% lift in average daily transaction value per user**, validating both **market potential** and **business viability**.

> This project demonstrates how **data analytics and experimentation** can transform product innovation into **measurable business growth**.

---

## 💼 Business Context

The **Indian credit card market** is highly competitive — dominated by established banks with **strong brand presence** and **deep customer loyalty**.  
Amidst this landscape, a **new entrant bank** sought to launch its **first credit card** and establish a distinctive identity.

To achieve this, the bank needed **data-driven launch strategy** that integrated:
- Deep **user insight analysis**
- Strategic **product design**
- Rigorous **statistical validation**

This ensured the credit card was **market-ready** and **positioned for success** — backed by evidence before scaling.

---

## 🎨 Phase 1 — Insight-Driven Design

The project began with a detailed understanding of the available data across three key tables:

- **Transaction Log** – complete record of customer transactions  
- **Credit Profile** – credit score, credit limit, and related attributes  
- **Customer Log** – demographics like age, income, gender, occupation  

### 🔍 Data Exploration & Cleaning

During EDA, several data quality issues were identified, including incorrect data types, missing values, outliers, and inconsistent entries.  
These were resolved using a combination of:

- **Business Logic:** validating credit score–limit relationships, aligning income brackets, fixing inconsistent customer attributes  
- **Statistical Techniques:** IQR-based outlier removal, Z-score filtering, and appropriate imputations for missing numeric and categorical fields  

This process ensured a clean and trustworthy dataset, forming the basis for insight generation and product design decisions.

👉 You can see all the data-cleaning strategies in this notebook:  
**Phase1_Design_Research.ipynb**

---

## 🔎 Insight Generation & Product Positioning

After cleaning the datasets, we explored user behavior to identify a market gap for positioning the new credit card.

### 🧠 Key Finding — Young Users Are Underpenetrated

- The **18–30 age group contributes 25% of credit inquiries but only 6% of active users.**  
- Mid-age professionals dominate credit card usage, showing a clear engagement gap among young customers.

📌 **Why the Gap Exists**

- **Limited Access:** Many young users lack credit history or stable income.  
- **UPI Preference:** This segment prefers UPI apps (GPay, PhonePe) for daily transactions.  

### 🔍 Deep Dive Into Young Users

Analysis revealed:

- **~80% transactions via UPI** → Suggests a Rupay UPI-linked card.  
- **Spending mostly on Amazon, Flipkart, Meesho** → Ideal for cashback incentives.  
- **High transaction value but low frequency** → They use credit cards mainly for high-value purchases, driven by instant discounts and No-Cost EMI.  

---

## 💳 Product Concept — Tailored for Young Customers

🎯 **Target:** Age 20–30, digital-first, limited credit history.  
💡 **Product:** Rupay Cashback Credit Card, optimized for online and UPI-native users.

### Key Features  
1️⃣ 5% Cashback on Amazon & Flipkart  
2️⃣ No-Cost EMI for high-value electronics  
3️⃣ Reward Points for daily UPI payments  

👉 Full insight breakdown is available in the notebook:  
**Phase1_Design_Research.ipynb**

---

## 🧰 Tools & Skills Used

**Analytical Tools** · Pandas · NumPy · Statsmodels · SciPy · Matplotlib · Seaborn  
**Statistical Skills** · A/B Testing  · Hypothesis Testing · Outlier Treatment  
**Product Skills** · Insight Synthesis · User Research · User Journey Mapping

