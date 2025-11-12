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

## 🧰 Tools & Skills Used

**Analytical Tools** · Pandas · NumPy · Statsmodels · SciPy · Matplotlib · Seaborn  
**Statistical Skills** · A/B Testing  · Hypothesis Testing · Outlier Treatment  
**Product Skills** · Insight Synthesis · User Research · User Journey Mapping


## 🎨 Phase 1 — Insight-Driven Design

### 📂 Data Sources
The analysis began by exploring three key datasets:
- **Transaction Log:** Complete record of customer transactions  
- **Credit Profile:** Credit score, credit limit, and risk attributes  
- **Customer Log:** Demographics such as age, income, gender, and occupation  

---

## 🔍 Data Exploration & Cleaning

During EDA, several issues surfaced — incorrect data types, missing values, outliers, and inconsistent fields.  
These were resolved using a mix of **business logic** and **statistical methods**:

- Validated credit score–limit relationships  
- Fixed demographic inconsistencies & aligned income brackets  
- IQR & Z-score based outlier removal  
- Numeric & categorical imputations for missing values  

This created a **clean, reliable dataset**, enabling accurate insight generation.

👉 *Detailed steps available in:* **Phase1_Design_Research.ipynb**

---

## 🔎 Phase 1 — Insight Generation & Product Positioning

### 🧠 Key Finding — Young Users Are Underpenetrated
- Users aged **18–30** contribute **25% of credit inquiries**  
- But only **6% become active card users**  
- Mid-age professionals dominate usage → **clear engagement gap**

### 📌 Why This Gap Exists
- **Limited Access:** Low credit history, unstable income  
- **UPI Dominance:** This segment prefers UPI apps (GPay, PhonePe) for everyday spending  

---

## 🔍 Deep Dive Into Young Users

Key behavioral patterns:
- **~80% transactions via UPI** → Opportunity for a *Rupay UPI-linked card*  
- High spending on **Amazon, Flipkart, Meesho** → Strong case for **cashback**  
- High value, low frequency → They use CC mainly for **discounts** & **EMI**  

---

## 💳 Product Concept — Designed for Young Customers

**🎯 Target:** Age 20–30, digital-first, limited credit history  
**💡 Product Idea:** *Rupay Cashback Credit Card* tailored for online + UPI-native users

### ⭐ Key Features
1. **5% Cashback** on Amazon & Flipkart  
2. **No-Cost EMI** on high-value electronics  
3. **Reward Points** on daily UPI payments  

👉 *See full insight breakdown in:* **Phase1_Design_Research.ipynb**

