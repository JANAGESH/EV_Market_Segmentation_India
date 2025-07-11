
# 🔍 EV Market Segmentation – India

This project applies unsupervised machine learning techniques to analyze and segment the Indian electric vehicle (EV) market using data from 2014 to 2023. It includes state-wise EV adoption patterns, clustering based on vehicle types, user sentiment analysis from reviews, and visualizations to support market insights.

---

##  Project Overview

In this project, we explored the Indian EV landscape through:

- State-wise EV adoption behavior by vehicle type (2W, 3W, 4W, Bus)
- Customer review-based clustering for 2W and 4W EVs
- Multiple visualizations to highlight sales trends and market dynamics

---

##  Machine Learning-Based Segmentation

We applied unsupervised learning techniques to uncover hidden patterns:

### 1. State-Level EV Clustering (EV Sales Data)
- **Model**: KMeans Clustering
- **Preprocessing**: One-hot encoding + Feature scaling using StandardScaler
- **Dimensionality Reduction**: PCA for 2D visualization
- **Output**: Segmented states into 4 clusters based on EV sales behavior

### 2. Review-Based Clustering (2W & 4W EVs)
- **Model**: TF-IDF + KMeans
- **Data**: Cleaned user reviews of 2W and 4W EVs
- **Output**: User segments based on satisfaction, performance, cost-sensitivity, etc.

### 3. Alternative Clustering: GMM
- **Model**: Gaussian Mixture Model (GMM)
- **Purpose**: Compare with KMeans for cluster consistency

---

## 📊 Visualizations Included

- Time-based trends (monthly, yearly)
- State-wise sales heatmaps
- Vehicle-type adoption distribution
- Word clouds for user reviews
- Clustering scatter plots using PCA/t-SNE
- Entropy-based diversity and sentiment analysis

---

## Technologies Used

- Python, Pandas, NumPy
- Scikit-learn (KMeans, PCA, GMM, TF-IDF)
- Matplotlib, Seaborn
- NLP: Text preprocessing + TF-IDF Vectorizer

---

## Key Insights

- States like Maharashtra, Delhi, and Karnataka lead in 4W and 2W EV adoption.
- Rural states show strong 3W adoption driven by e-rickshaw usage.
- Text-based clustering reveals performance and cost as key customer concerns.
- PCA and clustering reveal four distinct EV market segments across states.

---

## File Structure

- `EV_Indian_Market_Segmentation.ipynb` – Main analysis notebook
- `README.md` – Project overview and summary

---

## Authors

- Developed by Janagesh R as part of a market segmentation task during the Feynn Labs internship. This EV market analysis project focuses on segmenting the Indian electric vehicle market based on vehicle type using machine learning and data visualization techniques.

