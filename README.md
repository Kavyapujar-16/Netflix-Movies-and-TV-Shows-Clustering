# 🎬 Netflix Movies and TV Shows Clustering

A powerful Machine Learning project that clusters Netflix content based on various features like genre, country, release year, and duration. This clustering helps us identify meaningful patterns in content and enables business-driven insights through clear visualizations and dashboards.

---

## 📌 Project Overview

This project uses **K-Means Clustering** and **PCA** for dimensionality reduction to group similar Netflix titles into clusters. We explore the underlying structure of the data, validate clusters, and build dashboards with real-world business use cases.

---

## 🔍 Objectives

- Clean and preprocess the Netflix dataset  
- Apply feature engineering for better clustering  
- Use **PCA** to reduce dimensions for visualization  
- Apply **K-Means** clustering to group similar titles  
- Analyze cluster quality using **Silhouette Score**  
- Build insightful business use cases from clusters  

---

## 🗂️ Dataset

- **Source**: [Netflix Movies and TV Shows Dataset on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)  
- **Format**: CSV  
- **Records**: ~7,800+  
- **Features**: Title, Genre, Country, Rating, Duration, Release Year, etc.  

---

## ⚙️ Technologies Used

- **Python**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Scikit-learn** (PCA, KMeans, Silhouette Score)  
- **Jupyter Notebook**  
- **Streamlit** (for web app dashboard)  

---

## 🧠 Machine Learning Flow

```text
📂 Dataset 
   ↓
🧹 Data Cleaning 
   ↓
🧠 Feature Engineering 
   ↓
📏 Scaling 
   ↓
🔻 PCA (2D) 
   ↓
📍 KMeans Clustering 
   ↓
📈 Cluster Validation (Silhouette Score) 
   ↓
📊 Business Use Case Dashboards
```
---

## 📊 Business Use Cases (Visualized as Dashboards)

Cluster-wise Genre Popularity

Country-Based Content Clustering

Trending Release Year Analysis

Title Search & Cluster Lookup

Each use case is supported with beautiful, dashboard-style visualizations and dropdown filters.

## 🧪 Cluster Validation
Silhouette Score is used to validate the cluster separability.

Optimal k is selected using the Elbow Method.

🎯 Key Insights
Similar titles grouped together reveal hidden content trends

Helps Netflix-like platforms in recommendation engines

Enables business decisions like regional content targeting

## 📌 Folder Structure

📁 netflix-clustering/
├── 📄 netflix.ipynb                  # Main Jupyter Notebook
├── 📄 netflix business insights.ipynb # Business use case dashboards
├── 📄 requirements.txt              # Python dependencies
├── 📄 README.md                     # Project documentation
└── 📂 dataset/
    └── netflix_titles.csv           # Raw dataset

## 🏁 Conclusion
This project demonstrates how unsupervised learning can be used to uncover meaningful clusters in streaming content, enabling both user personalization and strategic content planning. The project is fully visualized and suitable for portfolio demonstration, interview presentation, or real-world business insights.
