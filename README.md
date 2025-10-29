# ⚡CredWise Lending Insights & Customer Behavior Analysis.

---
## Table of Contents

- **[Project Background](#project-background)**
- **[Bussiness Objectives](#business-objectives)**
- **[Executive Summary](#executive-summary)**
- **[ERD](#credWise-financial-services-dataset-erd)**
- **[Insights Deep Dive](#insights-deep-dive)**
    - **[Loan Portfolio Performance](#loan-portfolio-performance)**
    - **[Customer Behaviour And Income Analytics](#customer-behaviour-and-income-analytics)**
    - **[Regional And Temporal Lendig Trends](#regional-and-temporal-lending-trends)**
- **[Recommendations](#recommendations)**
  
---

## Project Background:
CredWise Financial Services is a U.S.-based digital lending company that provides personal and business loans across states like New Jersey, New York, Connecticut, and Massachusetts. With growing competition and rising loan defaults in some regions, the company wants to use data to better understand customer behavior, income patterns, and regional lending trends. The goal of this project is to identify risks, improve loan approval strategies, and ensure healthier portfolio growth across subregions.

---

## Business Objectives:
1. Loan Portfolio Performance Analysis
2. Customer Behavior & Income Analytics
3. Regional & Temporal Lending Trends

---

## Executive Summary:
Loan disbursements peaked in **2013** at **$148.6M** with the highest **interest rate** of **14.65%**, before declining in **2014–2015** as rates fell to **12.99%**. Income is heavily concentrated, with Debt Consolidation contributing **~65%** and, along with Credit Cards and Home Loans, making up over **90%** of revenues. Borrowers with Car and Home Loans show stronger repayment potential due to above-average balances, while Renewable Energy and Wedding Loans carry **~50%** lower balances, indicating higher risk. Regionally, **California and Texas** each exceeded **$21M** in **2013** and remain top contributors, while **GA, IL, MN**, and **VA** consistently underperform, highlighting the need to expand volumes, **strengthen reliable segments**, **manage high-risk loans**, and improve weaker markets.

---

## CredWise Financial Services Dataset ERD
 The Entity Relationship Diagram below outlines the relationships between the following Tables in Dataset
 ![](https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/ERD.png)


---



## Insights Deep Dive:

<p align="center">
<a name="loan-portfolio-performance"></a>
<img src="https://github.com/Pranshul-cloud/CredWise-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/Screenshot%202025-10-29%20090122.png" alt="Project Image" width="90%">
</p>    
<img src="https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/loan_portfolio_performance.visual" width="95%">


### Key Performance Indicators:
* **2013** marked the **peak year**, recording the **highest total loan amount** of **$148.6M** alongside the maximum **interest rate** of **14.65%**.
* **2014** and **2015** experienced a **decline** in both the **total loan amount** disbursed and the **average interest rate**.
* The average installment amount remained consistent across all years, indicating stability in repayment structures.
* The **Intrest rates** are Lowest in **2015** **12.99%** cutting down Margins.

  ---
<a name="customer-behaviour-and-income-analytics"></a>
<p align="center">
  <img src="https://github.com/Pranshul-cloud/CredWise-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/ChatGPT%20Image%20Oct%2029%2C%202025%2C%2008_33_00%20AM.png" alt="Project Image" width="40%">
</p>

<p align="center">
<img src="https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/customer_behaviour_income_analytics.visual" width="80%">
</p>


### Key Performance Indicators:
* Individuals taking loans for **Debt Consolidation**, **Credit Cards**, and **Home-related purposes**  account for the **majority** of loan-linked income. Together, these categories represent over **90%** of the **total annual income**, with **Debt Consolidation** alone contributing nearly **65%**.
* **Average Current Balance** of indivisuals with  **Cars** & **Home Loans** are slightly Higher than the average which shows Higher possibility of Loan payment on Time.
* **Average Current Balance** of indivisuals with **Renewable energy** & **Wedding Loans** is nearly half of the average which shows Lower possibility of Loan payment on Time.

 ---
 <a name="regional-and-temporal-lending-trends"></a>
<img src="https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/Regional_yearly_lending_trends.pivot" width="85%">

<img src="https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/Img/regional_yearly-lending_trends.visual" width="80%">



### Key Performance Indicators:
* **CA** and **TX** consistently have the **highest** values across all years, **peaking** in **2013** with over **$21 million** each. They are the top contributors among the top **10 states**.
* Almost all states saw a significant spike in **2013**, indicating a strong growth year compared to **2012**, **2014**, and **2015**. For example, **CA** went from **$6M** in **2012** to **$21M** in **2013**.
* After the **2013 peak**, **revenues** declined in **2014** and **2015** for all states. This may indicate market saturation or external factors affecting revenue.
* **GA**, **IL**, **MN**, **VA** consistently have the **lowest figures**, even during the **2013 peak**. These could be target states for performance improvement initiatives.

  ---

  ## Recommendations:

**1**  **Loan Portfolio Performance Analysis**
   Since 2015 showed the lowest interest rates (12.99%) and declining loan disbursements, the Company should focus on improving loan volume rather than depending on higher      margins.This can be donw by:
-  Expanding Credit Outreach.
-  Introducing  differentiated loan products(Education Loans , SME Loans).
-  Strengthening customer acquisition through partnerships and digital channels.

**2** **Customer Behavior & Income Analytics**
* Since Debt Consolidation, Credit Cards, and Home Loans contribute >90% of loan-linked income, continue prioritizing these categories with tailored products, competitive rates, and targeted marketing.
*  Leverage reliable segments: Borrowers with Car & Home Loans show stronger repayment potential; offer pre-approved top-up loans or cross-sell products (insurance, investments) to maximize wallet share.
*  Manage high-risk segments: Borrowers with Renewable Energy & Wedding Loans have lower balances, indicating higher default risk; tighten credit checks, limit exposure, or apply higher risk premiums.


**3** **Regional & Temporal Lending Trends**
* Maintain strong focus on California and Texas, which consistently lead revenues. Consider loyalty programs, premium products, or expanded distribution to sustain dominance and prevent competitor entry.
* Launch performance improvement initiatives such as localized marketing, partnerships, or customized loan/credit products to unlock untapped potential in these lagging regions.
* Analyze drivers behind the 2013 surge (policy changes, promotions, economic trends). Replicating those success factors could help revive growth in 2014–2015 levels.

---
* Check the [raw data](https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/data.csv)
* Check the [SQL Query:](https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/loan_analysis.sql)
* Check the Jypyter notebook for [Python codes:](https://github.com/Pranshul-cloud/Fintech-Lending-Insights-Customer-Behavior-Analysis/blob/main/loan_analysis.ipynb)
* Check more shuch projects on my [Portfolio website](https://preview--pranshul-analytics-hub-05.lovable.app/)

                            
