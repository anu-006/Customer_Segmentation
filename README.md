# Customer Segmentation using PCA and KMeans

## Short Description
Customer segmentation project using PCA and KMeans to uncover distinct behavioral groups from transactional data. The workflow reduces dimensionality with PCA, applies clustering, and interprets segments with actionable business insights for targeted marketing and sales campaigns.

## Problem
Modern businesses collect large volumes of customer data (income, spending, recency, purchase channels).  
This data is high-dimensional and noisy, making it difficult to identify meaningful customer segments.  
Without segmentation, marketing campaigns are generic, leading to wasted resources and poor customer engagement.

## Solution
This project applies **Principal Component Analysis (PCA)** to reduce dimensionality and highlight the most important behavioral features.  
- PCA compresses the dataset into fewer components while retaining most of the variance.  
- **KMeans clustering** is then applied to group customers into distinct segments.  
- The elbow method was used to determine optimal PCA components and cluster count.  
- Clusters were visualized using 2D PCA plots for interpretability.  

## Business Insights
The analysis revealed **four distinct customer segments**:

- **Premium Loyalists** → High income, high spend, consistent buyers. Strong candidates for loyalty rewards and premium offers.  
- **Casual Shoppers** → Moderate spenders with occasional purchases. Can be nurtured with personalized recommendations.  
- **Dormant Customers** → Low engagement, rare purchases. Require reactivation campaigns (discounts, reminders).  
- **Digital Deal Seekers** → Tech-savvy, respond well to online discounts. Ideal for digital-first campaigns.  

## Suggested Steps to Improve Sales / Target Campaigns
1. **Loyalty Programs** → Reward Premium Loyalists to retain high-value customers.  
2. **Personalized Upselling** → Offer tailored bundles and recommendations to Casual Shoppers.  
3. **Reactivation Campaigns** → Send targeted discounts or reminders to Dormant Customers.  
4. **Digital Promotions** → Focus online ads, flash sales, and app notifications on Digital Deal Seekers.  

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Scikit-learn)  
- PCA for dimensionality reduction  
- KMeans for clustering  
- Elbow method for component selection  

## Results
- Optimal PCA components: **6**  
- Optimal clusters: **4**  
- Clear customer segments identified with actionable insights for marketing and sales.  

## Business Value
By segmenting customers, businesses can:  
- Increase campaign ROI through targeted offers.  
- Improve customer retention with loyalty programs.  
- Reactivate dormant customers with personalized outreach.  
- Strengthen digital engagement by focusing on online-first segments.

## Customer Segmentation Output 
- <img width="689" height="547" alt="image" src="https://github.com/user-attachments/assets/cec00ddc-acc0-4b82-aec8-93a27b618d42" />

