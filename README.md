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

> During EDA, several data quality issues were identified, including incorrect data types, missing values, outliers, and inconsistent entries. These were resolved using a combination of **Business Logic.** and **Statistical Techniques.** This process ensured a clean and trustworthy dataset, forming the basis for insight generation and product design decisions.

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

 🔍 **Deep Dive Into Young Users***

Analysis revealed:

- **~80% transactions via UPI** → Suggests a Rupay UPI-linked card.  
- **Spending mostly on Amazon, Flipkart, Meesho** → Ideal for cashback incentives.  
- **High transaction value but low frequency** → They use credit cards mainly for high-value purchases, driven by instant discounts and No-Cost EMI.
  
---

## 💳 Product Concept — Tailored for Young Customers

🎯 **Target:** Age 20–30, digital-first, limited credit history.  
💡 **Product:** Rupay Cashback Credit Card, optimized for online and UPI-native users.

**Key Features**  
1️⃣ 5% Cashback on Amazon & Flipkart  
2️⃣ No-Cost EMI for high-value electronics  
3️⃣ Reward Points for daily UPI payments  

👉 Full insight breakdown is available in the notebook:  
**Phase1_Design_Research.ipynb**

---
## 🧪 Phase 2 — Experiment Design & A/B Testing

After finalizing the core features of the credit card, I moved to **Phase 2**, where the main goal was:

> **Will our newly designed credit card encourage users to make more day-to-day transactions and increase their average daily transaction value?**

---

## 🧮 Statistical Test Results (Two-Sample Z-Test)

| Metric                      | Control Group | Test Group                               |
| --------------------------- | ------------- | ---------------------------------------- |
| **Average Daily Spend**     | ₹221.18       | ₹235.98                                  |
| **Observed Lift**           | —             | **+6.7%**                                |
| **95% Confidence Interval** | —             | **[1.9%, 11.5%]**                        |
| **P-value**                 | —             | **0.0029** *(Statistically Significant)* |

💡 **Interpretation**

- The uplift is **real**, not random.  
- The new design increases daily spend by **2% to 11.5%**.  
- Our **business target uplift** was **10%** (the threshold for meaningful revenue impact).  
- The result (**6.7%**) is positive, but **slightly below the target**.  

---

## 📌 Final Recommendation

- ✅ **Keep the new design** — it is clearly improving user spending.  
- 🔧 Add **stronger incentives** (better cashback, e-commerce perks).  
- 🔁 **Rerun the experiment** with a larger sample or longer duration (e.g., 90 days).  
- 🚀 If uplift stabilizes **above 10%**, proceed with a **full-scale launch**.  

---

👉 **You can view the full experiment design and A/B testing analysis here:**  
**Phase2_ABTesting.ipynb**

---
