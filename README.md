# Advanced Data Analysis: Heart Dataset – Time Series, Sentiment, and Clustering

This project demonstrates the use of advanced data analysis techniques on a heart disease dataset.  
It involves **time series analysis, sentiment analysis on patient comments, and clustering** for pattern recognition and segmentation.

---

### 🔹 Key Objectives
1. **Time Series Analysis**
   - Decomposed `thalach` (maximum heart rate) to explore trends, seasonality, and residuals.
   - Applied **Exponential Smoothing** to forecast future heart rates.

2. **Sentiment Analysis**
   - Generated synthetic patient comments.
   - Applied **VADER SentimentIntensityAnalyzer** to quantify patient sentiment.
   - Visualized sentiment distribution using histograms.

3. **Text Mining**
   - Performed **Bag-of-Words vectorization** to identify the most common terms in patient comments.
   - Summarized frequently used words for better understanding of patient concerns.

4. **Clustering**
   - Standardized numerical features.
   - Applied **KMeans clustering** to segment patients based on heart metrics.
   - Reduced dimensions using **PCA** and visualized clusters in 2D.

---

### 🧰 Tools & Libraries Used
- **Pandas**, **NumPy** — Data manipulation  
- **Matplotlib**, **Seaborn** — Visualization  
- **Statsmodels** — Time series decomposition and forecasting  
- **NLTK** — Sentiment analysis  
- **Scikit-learn** — Scaling, PCA, KMeans clustering, text vectorization  

---

### 📊 Outcome
- Identified **trends and seasonal patterns** in heart rate using time series analysis.
- Extracted **patient sentiment patterns** from comments to understand satisfaction and concerns.
- Recognized **distinct patient segments** via clustering for potential personalized treatment approaches.
- Demonstrated the power of combining **structured and unstructured data analysis** in healthcare analytics.
