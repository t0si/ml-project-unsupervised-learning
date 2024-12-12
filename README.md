# Machine Learning Project - Unsupervised Learning

## **Project Outcomes**
This project focuses on applying **unsupervised learning techniques** to the "Wholesale Data" dataset. The analysis involves four main parts:
1. **Exploratory Data Analysis (EDA) and Pre-processing**
2. **K-Means Clustering**
3. **Hierarchical Clustering**
4. **Principal Component Analysis (PCA)**

---

## **Project Description**
In this project, we utilized unsupervised learning techniques to analyze and extract meaningful insights from the "Wholesale Data" dataset. The goal was to identify patterns and group similar data points using clustering techniques and dimensionality reduction.

The project involved the following tasks:

### **1. Exploratory Data Analysis (EDA) and Pre-processing**
- Imported and cleaned the dataset.
- Analyzed relationships between variables using data visualization tools.
- Handled missing values and outliers to ensure data quality.
- Applied feature engineering to enhance the dataset for better clustering performance.

### **2. Unsupervised Learning**
#### **K-Means Clustering**
- Applied K-Means clustering to segment the data into meaningful groups.
- Determined the **optimal number of clusters** using the **silhouette score** and **elbow method**.
- Visualized clusters and interpreted their characteristics.

#### **Hierarchical Clustering**
- Conducted hierarchical clustering to understand the hierarchical relationships among data points.
- Visualized the results using dendrograms to explore the dataset's natural grouping.

#### **Principal Component Analysis (PCA)**
- Performed PCA to reduce the dimensionality of the dataset while preserving the variance.
- Identified the most important features contributing to the principal components.
- Used PCA to visualize the data in two dimensions for better interpretability.

---

## **Key Insights**
- **K-Means Clustering**:
  - Optimal number of clusters: **2**
  - Cluster 0: High spending on **Grocery**, **Milk**, and **Detergents_Paper** (packaged goods).
  - Cluster 1: High spending on **Fresh**, **Frozen**, and **Deli** (fresh and specialty products).

- **Hierarchical Clustering**:
  - Revealed consistent grouping similar to K-Means clusters.
  - Highlighted relationships between data points at varying levels of granularity.

- **Principal Component Analysis (PCA)**:
  - **PC1**: Represented spending on **packaged goods** (Grocery, Milk, Detergents_Paper).
  - **PC2**: Represented spending on **fresh and specialty goods** (Fresh, Frozen, Deli).
  - PCA effectively reduced the dataset to 2 dimensions, explaining a significant portion of variance and enabling better visualization.

---

## **Visualizations and Metrics**
1. **Silhouette Analysis**:
   - Average silhouette score for optimal clusters (\( k=2 \)): **0.357**
2. **Dendrograms**:
   - Provided clear hierarchical grouping and cluster relationships.
3. **Cluster Profiles**:
   - Generated profiles for each cluster to summarize spending patterns and customer behaviors.

---

## **Challenges**
1. **Data Complexity**:
   - Handling outliers and scaling different spending categories posed challenges during pre-processing.
2. **Cluster Validation**:
   - Determining the optimal number of clusters required careful interpretation of metrics and visualizations.

---

## **Future Goals**
1. **Advanced Clustering Techniques**:
   - Experiment with other algorithms like DBSCAN or Gaussian Mixture Models to handle overlapping clusters.
2. **Enhanced Visualizations**:
   - Develop interactive dashboards for better stakeholder engagement.
3. **Feature Engineering**:
   - Incorporate additional domain-specific features to improve cluster interpretability.
4. **Deployment**:
   - Deploy the clustering model in a business scenario to generate actionable insights.

---

## **Tools and Libraries**
- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Machine Learning: `scikit-learn`
  - Visualization: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebooks

