# AI-Based-Customer-Segmentation

### 📌 Overview

This project applies **unsupervised machine learning** (K-Means Clustering) to segment customers into different groups based on their **annual income** and **spending score**. The goal is to help businesses like **Amazon or retail stores** better understand their customers and personalize marketing strategies accordingly.

---

### 📂 Dataset

**Mall Customer Segmentation Data**
📥 Download from: [Kaggle Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation)

* **Features:**

  * `CustomerID`
  * `Gender`
  * `Age`
  * `Annual Income (k$)`
  * `Spending Score (1–100)`

---

### 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas, NumPy
* Scikit-learn (KMeans)
* Seaborn, Matplotlib

---

### ✅ Key Steps

1. **Importing Libraries**
2. **Loading & Exploring the Dataset**
3. **Feature Selection & Scaling**
4. **Finding Optimal Clusters (Elbow Method)**
5. **Applying K-Means Clustering**
6. **Visualizing the Clusters**
7. **Analyzing Customer Segments**

---

### 📊 Visual Outputs

* Scatter plots of clusters
* Elbow graph to determine optimal `k`
* Cluster-based customer behavior insights

---

### 🎯 Business Applications

* 🎯 Personalized product recommendations
* 🎯 Targeted advertising for specific segments
* 🎯 Customer lifetime value prediction
* 🎯 Improve customer retention strategies

---

### 📌 Results

Identified **5 distinct customer clusters**, such as:

* High-income, high-spending users
* Low-income, low-spending users
* Average income but high interest
* Conservative spenders
* Young or budget-conscious shoppers

---

### 📁 File Structure

```
📁 AI_Customer_Segmentation/
│
├── Mall_Customers.csv
├── customer_segmentation.ipynb
└── README.md
```

---

### 💡 Future Enhancements

* Add 3D cluster visualizations
* Segment by **gender** or **age**
* Use other unsupervised models (DBSCAN, Hierarchical)
* Apply to **e-commerce** or **Amazon purchase** datasets

---

