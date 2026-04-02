#  Customer Segmentation using K-Means & Hierarchical Clustering

##  Overview
This project applies unsupervised learning techniques to segment e-commerce customers into meaningful groups based on their behavior and attributes.

The goal is to uncover hidden patterns in customer data to support better marketing strategies, personalization, and decision-making.

---

##  Features
- Data Cleaning & Preprocessing
- Feature Engineering (Age, Spending, Tenure, etc.)
- Outlier Detection & Removal
- One-Hot Encoding for categorical variables
- Feature Scaling using StandardScaler
- Dimensionality Reduction using PCA
- Clustering using:
  - K-Means
  - Agglomerative (Hierarchical) Clustering
- Cluster Evaluation:
  - Elbow Method (WCSS)
  - Silhouette Score
- Cluster Visualization (2D & 3D)
- Cluster Profiling & Insights

---

##  Dataset
- Dataset: `smartcart_customers.csv`
- Contains customer demographic and purchasing behavior data

---

##  Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kneed

---

##  Workflow

### 1. Data Preprocessing
- Handled missing values (Income column)
- Converted birth year → Age
- Converted customer date → tenure (days)
- Created new features:
  - Total Spending
  - Total Children

### 2. Feature Engineering
- Simplified Education categories
- Simplified Marital Status → Living_With
- Dropped irrelevant columns

### 3. Encoding & Scaling
- OneHotEncoding for categorical features
- Standardization using StandardScaler

### 4. Dimensionality Reduction
- PCA applied (3 components) for visualization and clustering efficiency

### 5. Clustering
- K-Means clustering
- Agglomerative clustering (Ward linkage)

### 6. Choosing Optimal K
- Elbow Method (WCSS)
- Silhouette Score

### 7. Visualization
- 3D cluster plots
- Heatmaps for correlation
- Scatter plots for spending vs income

---

##  Results & Insights
- Customers were segmented into distinct clusters based on:
  - Spending behavior
  - Income levels
  - Household composition
- Identified potential high-value and low-value customer groups
- Useful for targeted marketing and personalization strategies

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/sahilhardasani/ClusterCart.git

2. Install dependencies:
pip install -r requirements.txt


