# Uber Revenue Optimization 🚖📈

This repository contains my **Data Analyst Fellowship Graduation Project**, focused on analyzing Uber trip data to identify the **key drivers of revenue per trip**.  
The project combines **Python-based analysis** with an **interactive Tableau dashboard** to deliver actionable recommendations for business strategy.

---

## 📌 Project Overview
Uber runs millions of trips daily, but not every ride contributes equally to revenue.  
The purpose of this project is to:
- Analyze trip-level data to uncover revenue drivers  
- Test business hypotheses about distance, time, payment type, and locations  
- Provide **data-driven recommendations** to maximize revenue per ride  

---

## 🛠️ Methodology (10 Phases)

1. **Data Collection & Loading** – Imported trip-level dataset (~10M+ records).  
2. **Data Cleaning** – Removed 15k+ duplicates, fixed missing timestamps, dropped invalid rows.  
3. **Outlier & Anomaly Handling** – Filtered negative fares, zero-passenger trips, and extreme outliers.  
4. **Feature Understanding** – Defined key metrics: revenue per trip, revenue per mile, tip rate.  
5. **Exploratory Data Analysis (EDA)** – Visualized distributions, skewness, and correlations.  
6. **Revenue Distribution Analysis** – Quantile analysis showed top 1% trips earn 3x the median.  
7. **Hypothesis Testing** – Validated 7 business hypotheses (3 supported, 4 disproved).  
8. **Location & Time Insights** – Identified Newark Airport, Staten Island, and commute hours as revenue hotspots.  
9. **Dashboard Creation** – Built an interactive Tableau dashboard (*Uber: The Anatomy of a Money Trip*).  
10. **Recommendations & Next Steps** – Proposed strategies for tipping, dispatch, and pricing.  

---

## 📊 Key Insights
- **Credit card trips earn 40% more** than cash trips (97% of card trips included a tip).  
- **Airport trips (especially Newark)** generate up to **3x the median revenue**.  
- **Weekdays > weekends** in terms of average revenue per trip; Saturday is the weakest.  
- **Commute hours (6–7 AM, 4–5 PM)** are the most profitable time windows.  
- **Passenger count has no significant impact** on trip revenue.  

---

## 📑 Deliverables
- [Notebook: NL_uber.ipynb](./notebooks/NL_uber.ipynb)  
- [Final Report (PDF)](./reports/NL_Uber.pdf)  
- [Dashboard Snapshot](./reports/Dashboard.png)  

---

## 🚀 Recommendations
1. **Airport Specialist Program** – Incentivize drivers for frequent airport trips (Newark, JFK, LaGuardia).  
2. **Optimized Dispatch** – Prioritize drivers for high-value long-haul pickup zones like Staten Island.  
3. **Enhanced In-App Tipping** – Use dynamic tip suggestions (e.g., “$20 is common for airport trips”).  
4. **Strategic Commuter Pricing** – Adjust fares slightly during weekday peak hours.  
5. **Driver Opportunity Heatmaps** – Share data-driven “hot zones” with drivers via the app.  

---

## 🔮 Next Steps
- Conduct controlled **A/B testing** for tipping and commuter pricing features.  
- Build **predictive models** to forecast trip revenue before dispatch.  
- Integrate insights into Uber’s **driver and pricing strategy tools**.  

---

## 💵 Revenue Summary
- **Total Trips Analyzed**: ~1.25 million (sampled from 10M+)  
- **Total Revenue**: $50.9M  
- **Average Revenue per Trip**: $40.00  
- **Average Tips**: $5.81  
- **Top 1% Trips**: $114.96+ per trip (3x the median)  

---

## ⚙️ Requirements
To run the notebook, install dependencies:
```bash
pip install -r requirements.txt
```
---

## 👤 Author
**Ansh Jain**  
Business Analyst | Data Analyst Fellowship  

📧 [anshjain@example.com](mailto:anshjain@example.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/anshjain2u/) |
