## Customer Churn Analysis in Power BI

📌 Project Overview

Customer churn is one of the most critical challenges faced by subscription-based businesses, especially in the telecommunications industry. This project explores customer churn patterns for **Databel**, a fictional telecom company, using **Power BI** to uncover insights that can help reduce churn and improve customer retention.

While I had previously explored this dataset in Excel, I decided to rebuild the entire analysis in Power BI to take advantage of interactive visuals, deeper drill-downs, and a more stakeholder-friendly storytelling approach. The goal was to analyze churn and translate data into **clear, actionable business insights**.

---

## 🚀 Live Demo

You can explore the full dashboard here:  
🔗 **(https://app.powerbi.com/view?r=eyJrIjoiN2MxMjNkNTQtNTI1NC00OTNlLThiOTQtMWZhZDNhZTYzMGI2IiwidCI6IjFlNjMzNjFkLTJhODktNGMyNy04MTcwLTExNGE4MTVkZDA0ZiJ9)**

---

## 🎯 Business Problem

Databel is experiencing increasing customer churn and wants to understand:

- Which customers are most likely to churn  
- What behaviors and characteristics are strong churn indicators  
- How pricing, plans, payment methods, and customer service interactions affect retention  

The insights from this analysis are intended to support **decision-making across marketing, customer success, and product teams**.

---

## 🛠 Tool & Skills Used

- **Power BI**
  `Data modeling`
  `DAX measures`
  `Power Query`
  `EDA`

---

## 📂 Dataset Description

The dataset represents customer-level telecom data and includes:

- Customer demographics (`age`, `gender`, `senior status`)
- Contract and subscription details
- Group vs individual plans
- Usage behavior (`calls`, `data consumption`)
- Customer service interactions
- Payment methods
- Monthly and total charges
- Churn status and churn reasons

This data enables a holistic view of the customer lifecycle, from onboarding to churn.

---

## 📌 Key Insights & Findings

### 1️⃣ Group plans significantly reduce churn 
<img width="732" height="471" alt="Churn rate for group plans" src="https://github.com/user-attachments/assets/1cd82a36-7561-4009-93e8-4b9302a869e7" />


Customers on **group plans** pay around **$23** per month, compared with roughly **$33** for those on **individual plans.** The churn rate for group plans is also significantly lower than that of single plans, indicating that bundling services for families or friends reduces costs and enhances customer loyalty.

**Key takeaway:** Promoting group plans can improve retention while maintaining revenue stability.

---

### 2️⃣ Customer service calls are a strong churn signal

<img width="755" height="470" alt="Avg Customer Service Calls" src="https://github.com/user-attachments/assets/886bbc3a-eb78-44d5-82db-61b679b65ba0" />

Across the whole dataset, churned customers average **nearly one customer‑service call per account**, whereas non‑churned customers rarely exceed a few tenths of a call. When drilled down by state, the difference is even more interesting. Churned customers from states like `Vermont`, `Arizona`, and `Maine` average **between 2 and 3 calls**, while their non‑churn counterparts average less than 0.5 calls. **Frequent calls are therefore a red flag.** If people keep ringing your support line, there’s a good chance they’ll churn unless their issues are resolved quickly.

**Key takeaway:** Frequent service calls are an early warning sign. Proactive issue resolution could prevent churn before it happens.

---

### 3️⃣ Data consumption and payment method matter

<img width="751" height="435" alt="Churn rate by data consumption" src="https://github.com/user-attachments/assets/250ca94b-c8f7-423c-956f-bd975ea9e9fb" />

Churn rates are **highest** among customers using **between** `5 GB` and `10 GB` of data, at around 33%. For those consuming less than 5 GB, the churn rate is slightly lower, at about 32%. In contrast, heavy users who consume 10 GB or more have the lowest churn rate, at approximately 28%. Payment method has a bigger impact. Customers who pay by credit card have a churn rate of just 18.83%, while those using direct debit churn at 38.07%, and customers still using **paper cheques** churn at a staggering **47.52%.** Streamlining the payment experience and encouraging electronic payments could therefore have a positive effect on retention.

**Key takeaway:** Encouraging digital and automated payment methods could significantly improve retention.
                  Mid-tier users may feel underserved, presenting an opportunity for targeted offers or plan adjustments.

---

## 🧠 Business Recommendations

Based on the analysis, Databel could reduce churn by:

- Focusing on the **first few months of the customer journey**
- Promoting **group and bundled plans**
- Proactively monitoring customers with frequent support calls
- Streamlining payment processes and discouraging paper checks
- Tailoring offers for mid-tier data users

---

## 🖼 Dashboard Preview

> ![Customer Churn Analysis Power BI Business Intelligence Data Visualization Data Analytics Business Analysis_page-0001](https://github.com/user-attachments/assets/cadaddaa-ef80-4da3-b5d2-6ad5cc5840e5)

> ![Customer Churn Analysis Power BI Business Intelligence Data Visualization Data Analytics Business Analysis_page-0002](https://github.com/user-attachments/assets/48ae5660-f252-492e-aa9e-4ca4ea612e4e)

> ![Customer Churn Analysis Power BI Business Intelligence Data Visualization Data Analytics Business Analysis_page-0003](https://github.com/user-attachments/assets/825b34d6-b132-40e3-bbf2-11d630902db6)
 
---

Thanks for reading!
