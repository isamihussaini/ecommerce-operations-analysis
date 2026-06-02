# OLIST Supply Chain Risk Diagnostic
 
A delivery performance and revenue risk analysis built on 96,000 real e-commerce orders from the OLIST Brazilian e-commerce dataset.
 
Built with Excel and Power BI.
 
---
 
## The business question
 
Where is revenue leaking, and what is causing it?
 
Most e-commerce businesses track delayed orders as a customer service metric. This project treats them as a financial problem and quantifies the exposure.
 
---
 
## What the data showed
 
**The assumption was wrong.**
 
The initial hypothesis was that internal dispatch was causing delays. The data showed dispatch averaged 3 days, which is within a normal operational range. Transit time averaged 10 days. The problem was entirely in last-mile carrier delivery, not in the warehouse.
 
That distinction changes where you invest your budget to fix it.
 
**Revenue exposure was concentrated, not spread evenly.**
 
| State | Revenue at Risk |
|---|---|
| RJ | $350K |
| SP | $200K |
| BA | $170K |
| MG | $140K |
 
RJ and SP combined account for more than half the total exposure. Fix those two regions first.
 
**Delivery delays are also a retention problem.**
 
| Risk Category | Avg Review Score |
|---|---|
| Normal delivery | 4.31 |
| Slow delivery | 4.14 |
| High-risk delivery | 3.33 |
 
High-risk orders generated an estimated $263K in potential churn revenue. Late delivery does not just create a refund risk. It creates a repeat-purchase risk.
 
---
 
## Dashboard pages
 
**Page 1 — Performance Overview**
 
What is happening and how big is the problem. KPI cards showing total orders, average delivery days, delayed order percentage, and revenue at risk. Revenue share by delivery risk category. Dispatch vs transit day comparison.
 
**Page 2 — Geographic Performance**
 
Where is it happening. Average delivery time by state sorted worst first. Order volume and revenue by state with dual axis. State-level filter for drill-down.
 
**Page 3 — Revenue Exposure**
 
How much money is affected and where. Revenue at risk by state filtered to high-risk orders only. Risk distribution breakdown. Three-level action insight: which states to prioritize first, second, and monitor long-term.
 
**Page 4 — Customer Impact**
 
Are customers actually leaving because of it. Average review score by delivery risk category. Order distribution across risk tiers. Estimated churn risk in dollars.
 
---
 
## Key findings

Approximately 8% of total orders fall into delayed or high-risk delivery categories.
 
Delivery delays are driven by transit inefficiency, not internal dispatch failure.
 
15 to 16 percent of total revenue is exposed to high-risk delivery performance.
 
Two states (RJ and SP) carry more than 55 percent of total revenue at risk.
 
High-risk delivery orders produce review scores 23 percent lower than normal orders.
 
The problem is systemic across high-volume and mid-volume regions, not isolated to remote areas.
 
---
 
## Stack
 
| Layer | Tool |
|---|---|
| Data cleaning and preparation | Microsoft Excel |
| Dashboard and diagnostic | Microsoft Power BI |
| Dataset | OLIST Brazilian E-Commerce (public, Kaggle) |
 
---
 
## Related
 
I also built a free browser-based tool that estimates revenue exposure from delivery inefficiencies without requiring any raw data.
 
Four inputs. Instant output. Silent PDF download.
 
Live tool: https://isamihussaini.github.io/ecommerce-operations-risk-estimator
 
Also on ProductHunt: https://www.producthunt.com/products/e-commerce-operations-risk-estimator
 
---
 
## About
 
**Muhammad Sami Ullah** 

E-Commerce Operations Analyst
 
I diagnose delivery delays, dispatch inefficiencies, and inventory mismatches in e-commerce operations and quantify their revenue impact.
 
LinkedIn: https://www.linkedin.com/in/isamihussaini
Email: hussainimsami@gmail.com
