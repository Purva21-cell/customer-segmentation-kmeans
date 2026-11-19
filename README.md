# Customer Segmentation Using K-Means Clustering

##  Project Overview
This project applies **Machine Learning clustering techniques** to segment retail customers based on their purchasing behavior and numerical characteristics. Using the **K-Means clustering algorithm**, customers are grouped into distinct segments to help businesses better understand their customers and make data-driven marketing decisions.

The project uses the **Elbow Method** to estimate the optimal number of clusters and **Principal Component Analysis (PCA)** to visualize customer segments in a two-dimensional space.

##  Objectives
- Analyze retail customer data.
- Select relevant numerical features for clustering.
- Handle missing values using median imputation.
- Standardize features using `StandardScaler`.
- Determine the optimal number of clusters using the Elbow Method.
- Apply K-Means clustering to segment customers.
- Visualize clusters using PCA.
- Analyze customer segment characteristics and generate a report.

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

##  Machine Learning Algorithms & Techniques
- **K-Means Clustering** – Unsupervised learning algorithm for grouping similar customers.
- **Elbow Method** – Helps determine the optimal number of clusters.
- **Principal Component Analysis (PCA)** – Reduces feature dimensions to two components for visualization.
- **StandardScaler** – Standardizes numerical features.
- **Median Imputation** – Handles missing numerical values.

##  Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/customer-segmentation-kmeans.git
```

### 2. Navigate to the project directory

```bash
cd customer-segmentation-kmeans
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

### 4. Add your dataset

Place your retail dataset in the project directory and update the dataset path in the script if necessary.

```python
DATA_PATH = "retail_sales.csv"
```

The project supports CSV and Excel datasets.

### 5. Run the project

```bash
python main.py
```

##  Project Workflow

1. **Data Loading** – Load the retail dataset from CSV or Excel.
2. **Data Preparation** – Clean duplicate records and prepare customer-level data.
3. **Feature Selection** – Select relevant numerical features and remove identifier-like columns.
4. **Missing Value Handling** – Replace missing numerical values using median imputation.
5. **Feature Scaling** – Standardize numerical features using StandardScaler.
6. **Optimal Cluster Selection** – Use the Elbow Method to evaluate different cluster counts.
7. **Clustering** – Apply K-Means to group similar customers.
8. **Visualization** – Use PCA to project customer segments into two dimensions.
9. **Segment Analysis** – Analyze cluster sizes and average characteristics.
10. **Report Generation** – Export customer assignments, segment profiles, plots, and a summary report.

##  Results & Visualizations

### Elbow Method
The Elbow Method plots the Within-Cluster Sum of Squares (inertia) against the number of clusters. The curve helps identify a suitable cluster count where adding more clusters provides diminishing improvement.

### Customer Clusters Using PCA
PCA transforms the selected features into two principal components to visualize the distribution of customers across clusters.

### Customer Segment Analysis
The project generates:
- Customer cluster assignments
- Cluster sizes and percentages
- Average feature values for each cluster
- Silhouette scores for cluster evaluation

##  Output Files

| File | Description |
|---|---|
| `elbow_method.png` | Elbow plot for cluster selection |
| `customer_clusters_pca.png` | Two-dimensional cluster visualization |
| `customer_cluster_assignments.csv` | Customer-level cluster labels |
| `cluster_characteristics.csv` | Average feature profile per cluster |
| `cluster_sizes.csv` | Cluster counts and percentages |
| `pca_cluster_visualization_data.csv` | PCA coordinates with cluster labels |
| `customer_segmentation_report.txt` | Automatically generated project report |

##  Business Applications
Customer segmentation can help businesses:

- Develop targeted marketing campaigns.
- Identify high-value customers.
- Improve customer retention strategies.
- Understand purchasing behavior.
- Personalize offers and promotions.
- Support data-driven business decisions.

##  Future Improvements
- Implement hierarchical clustering and DBSCAN for comparison.
- Integrate RFM (Recency, Frequency, Monetary) analysis.
- Build an interactive dashboard using Streamlit.
- Improve cluster interpretation using additional customer attributes.
- Deploy the model as an interactive customer segmentation application.

##  Author
**Purva Ghate**

##  License
This project is intended for educational and learning purposes.

