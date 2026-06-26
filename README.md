# ga4-customer-journey-intelligence-dashboard
End-to-end customer journey analytics dashboard built using GA4, BigQuery, SQL, and Looker Studio.
# GA4 Customer Journey Intelligence Dashboard

## Project Overview

This project is an end-to-end business intelligence dashboard built using **Google Analytics 4 (GA4), BigQuery, SQL, and Looker Studio**.

The objective was to analyze customer behavior across the ecommerce journey and answer key business questions around acquisition, user engagement, conversion, and landing page performance.

Rather than connecting raw GA4 data directly to a dashboard, I designed analysis-specific datasets in BigQuery and transformed them into business-focused visualizations in Looker Studio.

---

## Business Questions

This dashboard answers four key questions:

* Where are users dropping off in the purchase funnel?
* Which acquisition channels generate the highest conversion rates?
* Which landing pages attract the most traffic?
* What actions can improve overall conversion performance?

---

## Tech Stack

| Technology               | Purpose                                 |
| ------------------------ | --------------------------------------- |
| Google Analytics 4 (GA4) | Event-level ecommerce data              |
| BigQuery                 | Data storage and SQL transformations    |
| SQL                      | KPI aggregation and analysis            |
| Looker Studio            | Dashboard development and visualization |

---

# Dashboard Structure

## 1. Executive Overview
<img width="510" height="386" alt="Ex_over" src="https://github.com/user-attachments/assets/2db5b969-aa27-4303-8adb-edbd7b080ad1" />

Provides a high-level summary of customer activity.

**KPIs**

* Total Users
* Product Views
* Purchases
* Overall Conversion Rate

---

## 2. Funnel Intelligence
<img width="475" height="357" alt="fu_in" src="https://github.com/user-attachments/assets/bb2a00f4-a0b9-4504-94da-f2f73b55d028" />


Analyzes user movement through the ecommerce funnel.

**Analysis Includes**

* Funnel stage conversion rates
* Funnel bottlenecks
* Critical drop-off points

---

## 3. Acquisition Intelligence
<img width="517" height="390" alt="ac_in" src="https://github.com/user-attachments/assets/6beab94c-15c2-4a53-b84b-c7bea5e33321" />


Evaluates the effectiveness of traffic sources.

**Analysis Includes**

* Users by acquisition source
* Purchases by channel
* Channel conversion rates

---

## 4. Landing Page Intelligence
<img width="510" height="388" alt="la_in" src="https://github.com/user-attachments/assets/7dbb5827-250d-446b-a9b5-8c192fbd938c" />


Analyzes entry pages and user engagement.

**Analysis Includes**

* Landing page traffic
* Homepage performance
* Category-level engagement

---

# Key Findings

* Analyzed **257,314 users** and **1.4M+ page views**
* Overall purchase conversion rate: **1.72%**
* Largest funnel drop-off (**79.5%**) occurred between **View Item → Add To Cart**
* Shop Google Merchandise Store traffic converted at **2.69%**, compared to **1.38%** for Google traffic
* Homepage accounted for the largest share of landing page traffic

# Skills Demonstrated

* Google Analytics 4 (GA4)
* BigQuery
* SQL
* Looker Studio
* Funnel Analysis
* Marketing Analytics
* Customer Journey Analysis
* Dashboard Design
* KPI Development
* Data Storytelling

---

# Repository Contents

```text
dashboard-screenshots/
dashboard-pdf/
README.md
```

---

## Future Improvements

* Add device and geographic segmentation
* Build interactive date filters
* Incorporate cohort and retention analysis
* Compare user behavior across marketing campaigns
GA4
 │
 ▼
BigQuery
(SQL Views & Tables)
 │
 ▼
Looker Studio
(4 Interactive Dashboards)
 │
 ▼
Business Recommendations
---

## Author

**Phani Geethika DV**


