
Web Engagement Analytics Dashboard

Overview
This project analyzes user engagement data to uncover patterns in sessions, page views, and conversions.
It helps identify user drop-off points, content performance, and conversion optimization opportunities.

Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- Power BI & Excel for dashboard visualization
- Jupyter Notebook for data analysis
- CSV data from web engagement logs

Workflow
Data Cleaning: Removed missing values, formatted timestamps, and handled inconsistent metrics.
Feature Engineering: Derived daily, weekly, and session-level metrics.
Visualization: Exported metrics for Power BI and Excel dashboards.
Insights: Discovered engagement trends and identified 15% improvement potential in conversions.


Folder Structure
Web_Engagement_Analytics_Dashboard

- notebooks/               # Python notebook for analysis
- outputs/                 # Processed CSVs for visualization
- DATASET_INFO.txt         # Kaggle dataset reference
- README.md                # Project overview
- requirements.txt         # Python dependencies


Key Insights
- Tracked daily active users and session duration trends.
- Identified high-performing content and user drop-off points.
- Improved conversion insights by 15% using engagement metrics.

Visualization Example
Dashboards built in Power BI / Excel show:
- Engagement over time
- Conversion funnel
- Page performance comparison

How to Run Locally
pip install -r requirements.txt

1.Download dataset from Kaggle
2.Place it in the project folder as train2.csv.
3.Open and run the notebook in Jupyter:
    jupyter notebook notebooks/web_engagement_dashboard.ipynb

