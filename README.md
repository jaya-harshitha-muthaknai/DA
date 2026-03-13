Crowdfunding Platform Analytics Dashboard

Project Overview:

Crowdfunding platforms connect startups with potential investors, enabling them to raise capital online. However, understanding platform performance requires analyzing multiple aspects such as user engagement, investor conversion, funding success, and capital efficiency.

This project analyzes a crowdfunding dataset using a full data analytics pipeline:

- SQL for answering business questions
- Python for data cleaning and preprocessing
- Power BI for interactive dashboard visualization

The objective is to uncover insights about user behavior, startup funding performance, and platform efficiency.

---

Problem Statement

Crowdfunding platforms generate large volumes of operational data including:

- User registrations
- Investor participation
- Startup funding goals
- Capital raised

Without proper analysis, it is difficult to identify:

- Where users drop off in the ecosystem
- How successful startups are in raising funding
- Whether capital is concentrated among a few startups
- How platform performance changes over time

This project builds an end-to-end analytics solution to answer these questions.

---

Tech Stack

Tool| Purpose
Python| Data cleaning and preprocessing
SQL| Business query analysis
Jupyter Notebook| Running SQL and Python analysis
Power BI| Dashboard visualization
DAX| Metrics and calculations

---

Project Workflow

1️⃣ Data Cleaning (Python)

The raw dataset was cleaned and prepared using Python.

Tasks performed:

- Handling missing values
- Removing duplicates
- Formatting columns
- Preparing data for SQL analysis

Python libraries used:

- pandas
- numpy

---

2️⃣ SQL Analysis (Jupyter Notebook)

SQL queries were written to answer key business questions such as:

- Percentage of active users
- Investor conversion rate
- Startup approval rate
- Funding success rate
- Capital efficiency of the platform
- Funding distribution across startups

The queries were executed using Jupyter Notebook.

---

3️⃣ Data Visualization (Power BI)

The cleaned data and SQL insights were visualized using an interactive Power BI dashboard.

The dashboard includes:

- KPI cards
- Funnel analysis
- Donut charts
- Funding distribution charts
- Time-series trend analysis

---

Key Business Questions

The dashboard answers the following important questions:

1. What percentage of users are active?
2. Is there a drop-off between users and investors?
3. How many users convert into investors?
4. Do verified users have a higher probability of becoming investors?
5. What is the startup approval rate?
6. What percentage of approved startups become fully funded?
7. What percentage of startups raise at least 50% of their funding goal?
8. Do startups with lower funding goals have higher success rates?
9. What is the average funding success across all startups?
10. What is the platform’s capital efficiency?
11. Is funding concentrated among a small number of startups?
12. What proportion of capital comes from the top 10% funded startups?
13. Where is the biggest drop-off in the ecosystem funnel?
14. Is the platform improving over time?

---

Key Insights

User Engagement

- Total Users: 10,000
- Active Users: 50.11%

Ecosystem Funnel

A noticeable drop-off occurs between users and investors, indicating potential barriers in the investment onboarding process.

Startup Approval

- Total Startups: 4000
- Approved Startups: 1343
- Approval Rate: 33.58%

Funding Success

- Total Funding Goal: 20.18B
- Total Amount Raised: 10.06B
- Average Funding Success: 49.85%

Capital Efficiency

The platform achieves approximately 49.85% capital efficiency, meaning nearly half of the requested funding is successfully raised.

Funding Distribution

Funding goals vary significantly across startups, suggesting that a small number of startups request significantly higher capital than others.

---

Dashboard Preview


Sample screenshots of the Power BI dashboard are included in this repository.  
These images provide a preview of the key visualizations used to analyze user engagement, funding success, and platform efficiency.

You can find the screenshots in the project folder.

---

Project Structure

Crowdfunding-Analytics/
│
├── data/
│   └── crowdfunding_dataset.csv
│
├── notebooks/
│   ├── sql_analysis.ipynb
│   └── data_cleaning.ipynb
│
├── powerbi/
│   └── crowdfunding_dashboard.pbix
│
├── images/
│   ├── funnel_chart.png
│   └── funding_trend.png
│
└── README.md

---

Future Improvements

- Predict startup funding success using machine learning
- Investor behavior analysis
- Funding trends by startup category
- Geographic analysis of startup funding

---

Author

Data analytics project combining Python, SQL, and Power BI to analyze crowdfunding platform performance.
