# Customer Marketing Segmentation with Machine Learning

This project uses unsupervised machine learning techniques to segment credit card customers based on their usage behaviors. The goal is to help the marketing department tailor products and services to specific customer segments.

## Dataset
The dataset includes approximately 9,000 credit card users and their usage patterns.

## Objectives
- Analyze customer data to identify segments.
- Utilize machine learning methods such as K-Means and PCA for segmentation.

## Methodology
1. **Data Exploration**: Analyze and visualize key trends and correlations.
2. **Data Cleaning**: Preprocess the data for analysis.
3. **K-Means Clustering**: Identify optimal customer segments using the Elbow method.
4. **Principal Component Analysis (PCA)**: Reduce dimensionality for better visualization.
5. **Autoencoder**: Apply a simple neural network for further analysis.

## Results
Eight customer segments were identified, including:
- **Revolvers**: High balances and cash advances.
- **Credit Purchasers**: Frequent payments in full.
- **Active Cash Buyers**: High purchase frequency and full payments.
- **VIP/Prime**: High credit limits with full payments.
- **Transactors**: Low balances and cautious spending.
- **Low Activity**: Infrequent usage of credit cards.

## Key Characteristics
Segments like "VIP/Prime" and "One-off" represent small outliers and may not constitute viable market segments.

## About
This project demonstrates the application of unsupervised machine learning for targeted marketing strategies in the credit card industry.

## Topics
- K-Means
- PCA
- Autoencoder
- Customer Segmentation
