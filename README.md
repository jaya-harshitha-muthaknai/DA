# Crowdfunding Platform Funnel & Data Integrity Analysis

## Project Overview

Crowdfunding platforms connect startups with investors, but their effectiveness depends on **user conversion efficiency, capital allocation, and data reliability**.

This project goes beyond traditional dashboarding by combining:

* **User lifecycle funnel analysis**
* **Conversion optimization insights**
* **Data integrity investigation**

The objective is to identify **system-level bottlenecks and quantify their impact on platform performance**.

---

## Problem Statement

Despite high user activity, crowdfunding platforms often struggle with:

* Low conversion from users to investors
* Inefficient capital distribution across startups
* Hidden data inconsistencies affecting business metrics

This project addresses both:

* **Business performance gaps**
* **Underlying data reliability issues**

---

## Key Analysis Areas

### 1. User Funnel Analysis

```
Registered → Verified → Active → Investor
```

**Key Findings:**

* Only ~14.89% of users complete full onboarding
* ~50% users are active, but most do not convert into investors

**Insight:**
The platform’s primary bottleneck is not user acquisition, but failure to convert already engaged users into investors.

---

### 2. Conversion & Engagement Insights

* Verified users are significantly more likely to become investors
* Large gap between active users and investor participation

**Insight:**
User verification acts as a critical conversion gate, indicating onboarding friction as a key constraint.

---

### 3. Startup Funding Performance

* Approval Rate: ~33.5%
* Average Funding Success: ~49.85%

**Insight:**
Nearly half of requested capital is not fulfilled, suggesting a mismatch between startup funding goals and investor demand.

---

### 4. Capital Distribution Analysis

* Funding is heavily skewed toward a small subset of startups
* Majority of startups receive limited funding

**Insight:**
The platform exhibits capital concentration, reducing success probability for mid-tier startups.

---

## Critical Data Integrity Issues Identified

* **Verified users retaining OTP values**
  → Failure in clearing authentication data

* **Active users without proper verification**
  → Incorrect user state transitions

* **Mismatch between user and investor records**
  → Data pipeline or relational inconsistencies

**Impact:**
These issues affect **data accuracy, KPI reliability, and platform security**, leading to flawed business decisions.

---

## Root Cause Analysis

* Inefficient user verification workflow
* Weak data lifecycle management
* Lack of validation rules between user states
* Possible backend synchronization gaps

---

## Key Takeaway

The platform’s biggest constraint is not user growth, but inefficient conversion of existing users into investors due to onboarding friction and inconsistent data handling.

---

## Strategic Recommendations

### 1. Optimize User Onboarding

* Remove OTP dependency post-verification
* Simplify verification flow
* Introduce guided onboarding

### 2. Strengthen Data Pipeline Integrity

* Enforce strict validation rules
* Remove inconsistent records
* Implement data quality audits

### 3. Improve Conversion Funnel Efficiency

* Target active but non-investing users
* Introduce trust signals
* Reduce friction in investment flow

### 4. Optimize Capital Allocation

* Promote mid-tier startups
* Adjust visibility of high-goal campaigns
* Introduce recommendation systems

---

## Business Impact

* Improved onboarding can increase investor conversion rates
* Fixing data inconsistencies ensures reliable KPI tracking
* Better capital distribution improves platform efficiency and startup success

---

## Tech Stack

* **Python (Pandas, NumPy)** – Data cleaning and preprocessing
* **SQL** – Business analysis
* **Power BI** – Dashboard visualization
* **Jupyter Notebook** – Analysis execution

---

## Dashboard Features

* Funnel visualization
* KPI metrics (conversion rates, funding success)
* Capital distribution insights
* Time-series trends

---

## Project Outcome

* Analyzed end-to-end platform performance
* Identified system-level data and process issues
* Delivered actionable business insights
* Demonstrated strong understanding of conversion funnels

---

## Future Improvements

* Build a startup funding success prediction model
* Perform investor segmentation
* Add category-wise and geographic insights
* Develop user conversion prediction models
