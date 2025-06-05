# 🧠 Credit Card Customer Segmentation

This project applies unsupervised machine learning (K-Means clustering) to segment credit card customers based on their demographics, spending behavior, and credit usage. The goal is to identify distinct customer profiles to support targeted marketing and product personalization strategies.

---

## 📌 Project Objectives

- Segment customers into meaningful clusters based on key financial indicators.
- Interpret each cluster to provide actionable business insights.
- Visualize customer distribution and key behavior patterns.
- Assist financial institutions in better decision-making and customer targeting.

---

## 📊 Dataset Overview

The dataset includes features such as:

- **Demographics**: Gender, Marital Status, Age, Dependents
- **Financial metrics**: Income, Credit Limit, Utilization Ratio
- **Behavioral data**: Months on book, Transaction count, Purchase amount

---

## 🔍 Key Steps

1. **Data Preprocessing**:
   - Handled missing values
   - Performed feature scaling
   - Created engineered features

2. **Exploratory Data Analysis (EDA)**:
   - Visualized distribution of customer traits
   - Assessed feature relationships via correlation and pairplots

3. **Clustering with KMeans**:
   - Applied the Elbow Method and Silhouette Score to determine optimal `k`
   - Segmented customers into 8 distinct clusters
   - Interpreted clusters to extract business value

4. **Visualization & Interpretation**:
   - Cluster-wise breakdown of average income, credit usage, and demographics
   - Business descriptions provided for each cluster profile

---

## 📈 Sample Cluster Insight

> **Cluster 6**:  
> 60% male, split between single and married, shows the highest transaction count and total amount, with high credit limits and above-average income. Likely to be high-value customers for upselling.

---

## 🛠 Tools Used

- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Scikit-learn for ML modeling
- Jupyter Notebook for implementation

---

## 📂 Files in Repository

- `Customer_Segmentation_Project.ipynb`: Full notebook with code, plots, and interpretation
- `customer_segmentation.csv`: Cleaned dataset used for modeling
- `.ipynb_checkpoints`: Jupyter notebook checkpoints (can be ignored)

---

## 🚀 Future Improvements

- Integrate t-SNE or PCA for dimensionality reduction & visualization
- Deploy as a Streamlit dashboard
- Explore other clustering techniques like DBSCAN or Gaussian Mixture Models

---

## 🤝 Let's Connect

If you're a recruiter, hiring manager, or fellow data scientist, feel free to connect or reach out!

