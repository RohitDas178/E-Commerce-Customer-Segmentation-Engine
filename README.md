# E-Commerce Behavioral Segmentation Engine (RFM Modeling)

## 📌 Project Overview
This project engineers an end-to-end data preparation and customer behavioral analytics pipeline. Using a raw e-commerce dataset of 541,000+ records, the pipeline cleans structural anomalies, mitigates extreme wholesale outliers, and utilizes RFM (Recency, Frequency, Monetary) modeling to segment 4,339 unique customers into actionable marketing cohorts.

## 🛠️ Tech Stack & Skills
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Concepts:** Data Cleaning, Feature Engineering, Outlier Handling (IQR), Behavioral Segmentation, Quantile Scoring

## 📊 Key Insights & Results
* **Data Scale:** Successfully processed **397,924 successful transactions** while isolating **8,905 product returns/cancellations**.
* **Outlier Control:** Identified and handled **156 extreme wholesale anomalies**, lowering overall transactional data distortion by **$1.70 per row**.
* **Strategic Cohorts:** Algorithmically segmented the customer base into distinct groups, discovering **1,137 high-value 'Champions'** and **276 'At Risk' customers** critical for retention targeting.

## 📂 Project Structure
* `ecommerce_customer_segmentation.ipynb` -> The complete production pipeline code.
* `README.md` -> Project documentation.
