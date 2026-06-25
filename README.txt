# 🛒 SmartCart - E-commerce Customer Segmentation System

A complete Machine Learning project that performs **customer segmentation using unsupervised learning**. This project analyzes customer demographics, purchasing behavior, and engagement to group customers into meaningful segments, helping businesses create personalized marketing strategies and improve customer retention.

---

## 📌 Project Overview

Traditional marketing campaigns often target all customers in the same way, leading to lower engagement and missed business opportunities.

This project uses **Machine Learning Clustering Algorithms** to discover hidden customer groups based on:

* Customer Demographics
* Annual Income
* Product Spending
* Purchase Frequency
* Website Activity
* Customer Response
* Complaint History

The generated customer segments help businesses identify:

* ⭐ Premium Customers
* 💰 Budget Customers
* 🎯 Potential Customers
* ⚠️ Churn-Risk Customers

---

## 📂 Dataset Information

* **Dataset Name:** SmartCart Customer Dataset
* **Total Customers:** 2240
* **Total Features:** 22

### Features Included

#### Customer Demographics

* ID
* Year_Birth
* Education
* Marital_Status
* Income
* Kidhome
* Teenhome
* Dt_Customer

#### Purchase Amount

* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds

#### Purchase Frequency

* NumDealsPurchases
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth

#### Customer Behaviour

* Recency
* Complain
* Response

---

# 🚀 Features

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Label Encoding
* Feature Scaling
* K-Means Clustering
* Hierarchical Clustering
* DBSCAN Clustering
* PCA Visualization
* Elbow Method
* Silhouette Score Evaluation
* Cluster Profiling
* Business Recommendations
* Model Saving
* Clustered Dataset Export

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Joblib
* Jupyter Notebook

---

# 📊 Machine Learning Algorithms

### K-Means Clustering

Used to divide customers into meaningful clusters based on purchasing behaviour.

### Hierarchical Clustering

Builds a dendrogram showing relationships between customer groups.

### DBSCAN

Detects dense customer groups and identifies outliers.

### PCA (Principal Component Analysis)

Reduces high-dimensional data into 2D for visualization.

---

# 📁 Project Structure

```
SmartCart-Customer-Segmentation/
│
├── smartcart_customers.csv
├── SmartCart_Customer_Segmentation_Project.ipynb
├── Customer_Segmentation_Result.csv
├── kmeans_model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
└── images/
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/SmartCart-Customer-Segmentation.git
```

Move to project directory

```bash
cd SmartCart-Customer-Segmentation
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# ▶️ How to Run

1. Open the notebook.
2. Place `smartcart_customers.csv` in the project folder.
3. Run all notebook cells.
4. View customer clusters.
5. Analyze business insights.
6. Export the clustered dataset.

---

# 📈 Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Feature Scaling
    │
    ▼
Elbow Method
    │
    ▼
K-Means Clustering
    │
    ▼
PCA Visualization
    │
    ▼
Cluster Analysis
    │
    ▼
Business Recommendations
```

---

# 📊 Example Customer Segments

### 🔵 Cluster 0 — Family Shoppers

* Families with children
* Frequent website visitors
* Respond well to discount campaigns
* Prefer value-for-money offers

### 🔷 Cluster 1 — Loyal Customers

* High income
* High spending
* Regular buyers
* Ideal for loyalty and membership programs

### 🟢 Cluster 2 — Premium Customers

* Highest income
* Highest product spending
* Prefer premium products
* Best customers for exclusive offers

### 🟡 Cluster 3 — Digital Browsers

* Visit website frequently
* Lower purchase rate
* Potential customers for personalized recommendations

---

# 📈 Results

* Successfully segmented 2240 customers into meaningful groups.
* Improved understanding of customer purchasing behaviour.
* Identified high-value and low-engagement customers.
* Enabled personalized marketing strategies.

---

# 💡 Business Applications

* Personalized Marketing
* Customer Retention
* Loyalty Programs
* Targeted Discounts
* Premium Membership Campaigns
* Churn Prediction Support
* Product Recommendation Systems

---

# 📚 Future Improvements

* Customer Lifetime Value (CLV) Prediction
* Real-Time Customer Segmentation
* Streamlit Web Application
* Interactive Power BI Dashboard
* Auto Cluster Selection
* Recommendation System Integration

---

# 👨‍💻 Author

**Tirthkumar Gabani**

Computer Engineering Student

Government Engineering College, Bhavnagar

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the **MIT License**.
