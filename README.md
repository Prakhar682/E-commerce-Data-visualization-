# 📊 End-to-End E-Commerce Sales & Customer Behavior Analytics

## 📌 Project Overview
This project delivers a deep-dive data analytics and business intelligence solution modeled around a year's transaction logging data from a UK-based online retail store (spanning **500,000+ data points**). The primary objective was to engineer features, diagnose supply chain operational frictions, analyze customer lifecycle retention, and provide data-backed strategic recommendations for B2B and B2C target segments.

## 🚀 Key Business Insights Discovered
* **High Customer Retention:** Uncovered a phenomenal **97.4% repeat purchase rate**, revealing that the storefront functions as a core supply chain wholesale node for smaller retail channels.
* **Supply Chain Diagnosis:** Identified a uniform **3.0% cancellation rate** across all structural product categories. Since deletions are bound to stock outs, this flat line points to central warehousing logistics constraints rather than single-product sourcing vulnerabilities.
* **Market Footprint:** Verified a strongly diversified international pipeline, where top geographic regions (Sweden, Canada, Germany, Belgium, Australia) consistently clear a **£9.2M+ sales baseline**.
* **B2B Purchasing Density:** While daily retail consumer baskets center under £400, a heavy right-skewed distribution scaling to £900 isolates a dense clustering of bulk enterprise procurement operations.

## 🛠️ Tech Stack & Methods Used
* **Data Processing & Cleaning:** Python, Pandas (Datetime normalization, handling structured cancellations mapping).
* **Feature Engineering:** Calculated overall transaction weights (`Total_Amount = Quantity * Price`) to monitor gross sales distributions.
* **Advanced Aggregations:** Temporal tracking via Month-End (`ME`) sequential resampling and weekly distribution grouping.
* **Data Visualization:** Seaborn and Matplotlib (Density Histograms with KDE layers, Sorted Horizontal Bar Charts, Pie charts, and Multi-chromatic Time-Series plots).

<img width="3000" height="1500" alt="weekday_purchasing_pattern" src="https://github.com/user-attachments/assets/a46858da-9423-43c2-be77-03af08ff06f8" />
<img width="3600" height="1500" alt="transaction_trend_over_time" src="https://github.com/user-attachments/assets/54103f7e-2868-4bdb-854f-bb0b60ab8fba" />
<img width="3000" height="1500" alt="revenue_by_category" src="https://github.com/user-attachments/assets/b02a8e59-9ced-4cad-928a-b77bd8cde62c" />
<img width="2100" height="2100" alt="repeat_vs_onetime_customers" src="https://github.com/user-attachments/assets/386fd1d5-c55d-4098-a1bf-b1be814f54ef" />
<img width="3000" height="1500" alt="distribution_of_transactions" src="https://github.com/user-attachments/assets/7e308be1-5f55-4ce2-a69d-35a23ba2af6a" />
<img width="3000" height="1500" alt="customer_behaviour_top_countries" src="https://github.com/user-attachments/assets/f412256b-6e48-48b1-9a62-97070cda8839" />
<img width="3000" height="1500" alt="cancellation_rate_by_category" src="https://github.com/user-attachments/assets/81bf4250-a1a9-47f9-8445-70d92080b471" />


## 📂 Repository Structure
```text
├── Ecommerce_Transactions_Data.csv  # 500K Rows Core Transaction Dataset
├── main.py                          # Modular Production-Grade Python Script
├── Data_Visualisation_Report.pdf    # Executive Summary & Analytical Breakdown
└── Visualizations/                  # High-Resolution Exported Plots (.png)

