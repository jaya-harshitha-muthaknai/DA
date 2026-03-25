

#  **Crowdfunding Platform Funnel & Data Integrity Analysis**
## **Project Overview**

Crowdfunding platforms connect startups with investors, but their effectiveness depends on **user conversion efficiency, capital allocation, and data reliability**.

This project goes beyond traditional dashboarding by combining:

* **user lifecycle funnel analysis**
* **conversion optimization insights**
* **data integrity investigation**

The objective is to identify **system-level bottlenecks and quantify their impact on platform performance**.

---

## **Problem Statement**

Despite high user activity, crowdfunding platforms often struggle with:

* Low conversion from users to investors
* Inefficient capital distribution across startups
* Hidden data inconsistencies affecting business metrics

This project addresses both:

* **business performance gaps**
* **underlying data reliability issues**

---

## **Key Analysis Areas**

### **1. User Funnel Analysis**

A complete lifecycle funnel was constructed:

```
Registered → Verified → Active → Investor
```

### **Key Findings:**

* Only **~14.89% of users complete full onboarding**
* ~50% users are active, but a **majority fail to convert into investors**

### **Insight:**

> The platform’s primary bottleneck is not user acquisition, but **failure to convert already engaged users into investors**.


### **2. Conversion & Engagement Insights**

* Verified users show significantly higher likelihood of becoming investors
* Large gap between **active users and investor participation**

### **Quantified Insight:**

> User verification acts as a critical conversion gate, with verified users significantly more likely to transition into investors, indicating onboarding friction as a key constraint.


### **3. Startup Funding Performance**

* Approval Rate: ~33.5%
* Average Funding Success: ~49.85%

### **Insight:**

> Nearly half of requested capital is not fulfilled, suggesting a **misalignment between startup funding goals and investor demand**.

---

### **4. Capital Distribution Analysis**

* Funding is heavily skewed toward a small subset of startups
* Majority of startups receive limited funding

### **Insight:**

> The platform exhibits **capital concentration**, reducing visibility and success probability for mid-tier startups.


## 🚨 **Critical Data Integrity Issues Identified**

This analysis uncovered significant system-level inconsistencies:

* **Verified users retaining OTP values**
  → Indicates failure in clearing authentication data

* **Active users without proper verification**
  → Suggests incorrect user state transitions

* **Mismatch between user and investor records**
  → Points to data pipeline or relational inconsistencies

### **Impact:**

> These issues compromise **data accuracy, KPI reliability, and platform security**, leading to potentially flawed business decisions.

## **Root Cause Analysis**

The observed issues indicate:

* Inefficient **user verification workflow**
* Weak **data lifecycle management**
* Lack of **validation rules between user states**
* Possible **backend synchronization gaps**

---

## 📌 **Key Takeaway**

> The platform’s biggest constraint is not user growth, but inefficient conversion of existing users into investors, driven by onboarding friction and inconsistent data handling.

---

## **Strategic Recommendations**

### **1. Optimize User Onboarding**

* Remove OTP dependency post-verification to prevent inconsistent states
* Simplify verification flow to reduce drop-offs
* Introduce guided onboarding for new users

---

### **2. Strengthen Data Pipeline Integrity**

* Enforce strict validation rules for user states
* Eliminate inconsistent records (e.g., verified users with OTP)
* Implement periodic data quality audits

---

### **3. Improve Conversion Funnel Efficiency**

* Target active but non-investing users with personalized nudges
* Introduce trust signals (verified badges, campaign transparency)
* Reduce friction in investment flow

---

### **4. Optimize Capital Allocation**

* Promote mid-tier startups to improve funding distribution
* Adjust visibility of high-goal campaigns
* Introduce recommendation systems for investors

---

## 📈 **Business Impact**

* Improving onboarding can significantly increase **investor conversion rates**
* Fixing data inconsistencies ensures **accurate KPI tracking and better decisions**
* Optimizing capital distribution improves **platform efficiency and startup success rates**

---

## **Tech Stack**

* **Python (Pandas, NumPy)** → Data cleaning & preprocessing
* **SQL** → Business query analysis
* **Power BI** → Interactive dashboard
* **Jupyter Notebook** → Analysis execution

---

## **Dashboard Features**

* Funnel visualization of user lifecycle
* KPI metrics (conversion rates, funding success)
* Capital distribution insights
* Time-series funding trends

---

## **Project Outcome**

This project demonstrates:

* End-to-end analysis of a **platform-based business system**
* Identification of **data integrity and system design issues**
* Ability to translate data into **strategic, actionable insights**
* Strong understanding of **conversion funnels and business optimization**

---

## **Future Improvements**

* Build a **startup funding success prediction model**
* Perform **investor segmentation and behavior analysis**
* Add **category-wise and geographic insights**
* Develop **user conversion prediction models**

