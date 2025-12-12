# 📊 Customer Segmentation Using K-Means Clustering

This project applies **K-Means Clustering**, an unsupervised machine learning technique, to segment mall customers based on their **Annual Income** and **Spending Score**. The goal is to identify meaningful customer groups that can help businesses improve marketing strategies, target customers effectively, and enhance decision-making.

---

## 🚀 Project Overview

* Performed clustering using **Annual Income (k$)** and **Spending Score (1–100)**
* Used **StandardScaler** to normalize features
* Applied **Elbow Method** to determine optimal number of clusters
* Selected **K = 5** based on WCSS analysis
* Visualized clusters using scatterplots with centroids
* Exported final clustered dataset as `clustered_customers.csv`

---

## 🧠 Technologies & Libraries Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn (KMeans, StandardScaler)**

---

## 📁 Dataset

* **Mall Customers Dataset**
* Contains 200 customer entries with fields such as:

  * Gender
  * Age
  * Annual Income (k$)
  * Spending Score (1–100)

---

## 🔍 Steps Performed

### **1. Data Loading & Preprocessing**

* Loaded dataset using Pandas
* Selected relevant features
* Scaled values using StandardScaler

### **2. Determining Optimal K**

* Computed WCSS for K = 1 to 10
* Plotted Elbow Curve
* Optimal K = **5**

### **3. Applying K-Means**

* Trained K-Means model with 5 clusters
* Predicted cluster labels
* Plotted clusters with centroids

### **4. Exporting Results**

* Added cluster labels to dataset
* Saved processed data as `clustered_customers.csv`

---

## 📈 Visual Outputs

✔ Elbow Method Plot
✔ Customer Segmentation Scatter Plot
✔ Cluster Centroids Visualization

(You can add your uploaded images here if you want)

---

## 📝 Running the Code

Run the script:

```bash
python "Mall Customers Dataset.py"
```

Make sure the dataset file `Mall_Customers.csv` is in the same directory.

---

## 📦 Output Files

* **clustered_customers.csv** → file with cluster labels
* **Cluster visualizations** (PNG images)
* Updated plots for analysis

---

## 🎯 Key Learnings

* Understanding of **unsupervised learning**
* Feature scaling & preprocessing
* Clustering techniques for customer segmentation
* Visualizing clusters effectively
* Using WCSS & Elbow Curve for model selection

