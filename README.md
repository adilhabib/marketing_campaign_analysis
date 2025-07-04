# 📊 Marketing Campaign Performance Analysis

This project explores and visualizes customer response data from a multi-channel marketing campaign to uncover patterns in engagement, spending, and segment-wise performance. Built using Python and Tableau, it answers key business questions like:

- Which campaigns performed best overall?
- What customer segments (age, education, marital status) were most responsive?
- How does spending behavior relate to campaign acceptance?
- Where should marketers focus future budget and effort?

---

## 📁 Project Structure

marketing_campaign_analysis/
│
├── data/
│ └── marketing_campaign.csv # Original dataset (Kaggle)
│ └── marketing_cleaned.csv # Cleaned version for Tableau
│
├── notebooks/
│ ├── 01_data_cleaning_and_eda.ipynb # Data cleaning + EDA
│ └── 02_campaign_analysis.ipynb # Campaign-wise deep dive + ROI logic
│
├── visualizations/
│ ├── tableau_dashboard.twbx # Tableau dashboard file
│ └── charts/
│ ├── channel_response_rate.png
│ ├── response_by_age_group.png
│ └── campaign_heatmap.png
│
├── outputs/
│ ├── campaign_total_acceptances.csv
│ └── campaign_response_rate.csv
│
└── README.md
