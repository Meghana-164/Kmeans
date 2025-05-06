# Mall Customer Segmentation using K-Means Clustering

##  Objective
Perform **unsupervised learning** on mall customer data to segment customers into distinct groups based on their behavior using **K-Means Clustering**.

---

## 📁Dataset
**Source**: Mall Customers Dataset  
**Attributes**:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- PCA (for dimensionality reduction)

---

##  Steps Performed

1. **Data Preprocessing**
   - Encoding categorical data (`Gender`)
   - Selecting relevant features

2. **Elbow Method**
   - Used to determine the optimal number of clusters (K)
   - Chose `K = 6` based on the elbow point and silhouette score

3. **Clustering**
   - Applied K-Means Clustering
   - Added cluster labels to original data

4. **Dimensionality Reduction**
   - Used PCA to reduce feature space to 2D for visualization

5. **Evaluation**
   - Calculated **Silhouette Score** for clustering quality
   - Score for K=6: `0.452` (indicates moderate to good separation)

6. **Visualization**
   - Scatter plot of clusters using PCA-reduced data

---

##  Results
| Cluster | Avg Age | Avg Income (k$) | Avg Spending Score |
|---------|---------|-----------------|---------------------|
| (You can fill this table from your grouped data summary) |

**Insights**:
- Some clusters represent high-income, low-spending customers.
- Others include younger customers with high spending scores, etc.

---

