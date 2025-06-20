# 📊 Hierarchical Clustering with Dendrogram (CSV Data)

This project demonstrates how to perform **hierarchical clustering** on a dataset stored in a CSV file and visualize the results using a **dendrogram**. The clustering is performed using the `Ward` linkage method from the `scipy` library.

---

## 📁 Dataset

The dataset is expected to be in CSV format and contain only numerical values (features). The first column should be used as the **row index** (labels for data points).

Example:
```csv
Index,Feature1,Feature2
A,1.0,2.0
B,1.5,1.8
C,5.0,8.0
D,8.0,8.0
