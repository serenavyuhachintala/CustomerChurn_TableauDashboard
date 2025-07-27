# CustomerChurn_TableauDashboard
Tableau dashboard analysing churn patterns by Serena Vyuha Chintala

## Project Overview
This project explores customer churn patterns for a fictional telecom company. Built in Tableau, the dashboard delivers interactive insights around churn behavior across contract types, tenure, demographics, and service usage.

The goal is to empower stakeholders with actionable data that can guide retention strategies and improve customer loyalty.

 **Interactive Dashboard Live:**  
 [View on Tableau Public](https://public.tableau.com/app/profile/serena.vyuha.chintala/viz/CustomerChurnDashboard_17536311585570/CustomerChurnDashboard)

---

## Dataset
**Source:** [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
**Records:** 7,043 customers  
**Fields:** Demographics, contract details, monthly/total charges, service usage, churn status

---

## Business Problem
Customer churn is a critical challenge for subscription-based services. The objective of this project was to uncover:
- Which types of customers are most likely to churn?
- What service-related or demographic factors correlate with churn?
- How can the business act proactively to reduce churn?

---

## Visuals & Insights

### 1. Churn by Contract Type
- **Insight:** Customers on month-to-month plans show significantly higher churn than those on annual contracts.
- **Action:** Offer discounts or loyalty perks for annual plans.

![Churn by Contract Type](https://github.com/serenavyuhachintala/CustomerChurn_TableauDashboard/blob/main/Churchrate_contracttype.png?raw=true)

---

### 2. Churn by Senior Citizen
- **Insight:** Non-Senior citizens show a moderately higher churn rate than seniors.
- **Action:** Improve digital support & outreach to retain older customer segments.

![Churn by Senior](https://github.com/serenavyuhachintala/CustomerChurn_TableauDashboard/blob/main/Churn_bysenior.png?raw=true)
---

### 3. Scatterplot: Tenure vs Monthly Charges
- **Insight:** A large portion of churners are clustered in the **low-tenure, high-bill** quadrant.
- **Action:** Flag and engage new customers who face high charges early on.

![Scatterplot – Charges vs Tenure](https://github.com/serenavyuhachintala/CustomerChurn_TableauDashboard/blob/main/Churn_chargevstenure.png?raw=true)
---

### 4. Interactive Dashboard View
- Includes filter for **Contract Type** that refreshes visuals on the fly.
- Dashboard layout supports intuitive exploration for business users.

![Dashboard Screenshot](https://github.com/serenavyuhachintala/CustomerChurn_TableauDashboard/blob/main/Customer%20churn%20dashboard.png?raw=true)

---

## Key Features
- Interactive dashboard built using **Tableau Public**
- Clean layout optimized for storytelling and exploration
- Dynamic filter by **Contract Type** for deep-dive analysis
- Clear separation of key churn drivers: demographics, contracts, tenure, and billing
- Designed for non-technical business users to explore and act on churn patterns

---

## Business Recommendations
- **Promote longer-term contracts** to reduce churn — particularly for month-to-month customers
- **Investigate churn among non-senior customers** — offer value-driven onboarding or early engagement incentives
- **Target new customers with high monthly charges** for personalized retention offers within the first few months
- Bundle services and support (e.g. Tech Support, Online Backup) to improve stickiness


---

## Next Steps
- Add **predictive churn modeling** in Python or R
- Create a second dashboard for **Retention Campaign ROI Tracking**
- Embed dashboard in a mock executive report (PDF or Slide Deck)

---

Connect with me on [LinkedIn](https://www.linkedin.com/in/serenavyuhachintala/)
Or explore more projects on my [Tableau Public](https://public.tableau.com/app/profile/serena.vyuha.chintala)

