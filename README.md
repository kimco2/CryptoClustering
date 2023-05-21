# Predicting whether cryptocurrencies are affected price changes

### **Overview**
Predicted whether cryptocurrencies are affected by 24-hour or 7-day price changes using python and unsupervised learning to cluster cryptocurrencies with a K-means algorithm.

### **Aspects covered**
- Using K-means to cluster Cryptocurrencies
- Using the elbow method to find the optimal value of K for clustering the data
- Initialising, fitting and predicing the clusters for grouping the cryptocurrencies
- Using hvPlot to create scatter plots with colour-coded labels for  different clusters.

### **Outcome**
Two models were run
- The first model using the original data
- The second using PCA to reduce the dimensionality of the data to three principal components.
 
![crypto_k_means](crypto_k_means.png)
![crypto_scatter](crypto_scatter.png)

After visually analysing the cluster analysis results, there is less inertia in the PCA model, the points are closer together and the clusters are more clearly defined.  Also the PCA scatter plot better separates out the two outliers (ethlend and celsius-degree-token).

### **Folder structure**
- '*Crypto_Clustering.ipynb*' contains the code, analysis and output
- The folder '**Resources*' holds the data file.

<br>

---

### **Contact**
Email: kymcoleman@gmail.com

---

