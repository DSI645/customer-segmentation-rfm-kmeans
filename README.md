# Customer Segmentation with RFM + K-Means

Segmenting customers using **Recency, Frequency, and Monetary (RFM)** features and **K-Means clustering** to identify high-value, loyal, and at-risk groups.  
Built in Python with pandas, scikit-learn, and matplotlib.

## 🔍 What’s inside
- Clean & reproducible **Jupyter Notebook**
- **RFM feature engineering**
- **Elbow method** to choose k
- **Cluster labeling & visuals**
- Lightweight **sample dataset** for quick runs

## 🗂️ Project structure
```
customer-segmentation-rfm-kmeans/
  ├─ customer_segmentation.ipynb
  ├─ data/sample_transactions.csv
  └─ assets/{elbow_curve.png, cluster_scatter.png}
```

## 🚀 Quickstart
```bash
pip install -r requirements.txt
# Open notebook and run all cells
```

## 📊 Results (preview)
![Elbow Curve](assets/elbow_curve.png)
![Clusters](assets/cluster_scatter.png)

## 🧠 Method (RFM)
- **Recency:** days since last purchase  
- **Frequency:** number of invoices  
- **Monetary:** total spend  

We scale RFM, run **K-Means**, analyze segment means, and visualize cluster separation.

## 📎 Data
Sample included in `data/`. Original dataset: Online Retail (UCI/Kaggle). Replace with your own transactional data to reproduce at scale.

## ✅ Use cases
- Targeted marketing & promos  
- Churn prevention for at-risk segments  
- Priority service for top spenders  

## 🧩 Next steps
- Add silhouette score & PCA visualization  
- Try alternative clustering (GMM/DBSCAN)  
- Build a simple Streamlit app for interactive segmentation

---

**Author:** Oluwatobiloba Dahunsi · [GitHub](https://github.com/DSI645)
