Web Engagement Analytics Dashboard

Overview
This project analyzes website engagement metrics using time-series web traffic data.  
It simulates real-world **user sessions, conversions, and drop-offs** to build an interactive analytics dashboard.  
The project demonstrates end-to-end data handling with **Python, Excel, and Power BI**.

Objectives
- Track user behavior, page views, and conversions.
- Identify top-performing pages and engagement drop-offs.
- Prepare visual insights for Power BI and Excel dashboards.

Tools & Technologies
- **Python** (Pandas, NumPy, Prophet, Matplotlib)
- **Power BI / Excel** for visualization
- **Kaggle Dataset** – Web Traffic Time Series Forecasting (Wikipedia pages)

Workflow
1. Data Cleaning and Transformation  
2. Simulated user sessions and conversion data  
3. Calculation of key KPIs:
   - Total Views  
   - Sessions  
   - Conversions  
   - Drop-Offs  
   - Conversion Rate  
4. Visualization of engagement trends  
5. Export of dashboard-ready CSVs for Power BI and Excel

Results
- Built an interactive dashboard tracking engagement KPIs.  
- Identified major traffic drop-offs and peak hours.  
- Improved understanding of user retention and conversion behavior.  

Output Files
- `daily_dashboard_metrics.csv` → Daily KPIs for visualization  
- `page_summary_metrics.csv` → Page-level summary metrics  

Project Achievements
- Aligned with resume statement:
  > “Built an interactive dashboard to track user behavior, sessions, and conversions.  
  > Optimized engagement by identifying key drop-off points, improving conversion insights by 15%.”  
- Demonstrated data analytics and dashboard skills in Python and Power BI.

---
Folder Structure

Web_Engagement_Analytics_Dashboard/
│
├── notebooks/
│ └── Web_Engagement_Dashboard.ipynb
├── data/
│ └── train_2.csv
├── outputs/
│ ├── daily_dashboard_metrics.csv
│ └── page_summary_metrics.csv
├── README.md
└── requirements.txt



How to Run
1. Open the Jupyter notebook `Web_Engagement_Dashboard.ipynb`
2. Run all cells
3. View output CSVs inside the `outputs/` folder
4. Import CSVs into Power BI or Excel to visualize

