# Crypto Clustering
module 19 repo challenge

<p align="center">
<img src="Images/crypto.jpeg" alt="crypto graphic" width="500" height="300"  >
</p>
  
---
## Table of Contents

- [Background](#background)
- [Part 1: Challenge Layout](#layout)
- [Part 2: Results](#result)
- [Part 3: Conclusion](#conclusion)

---
## Background <a name="background"></a>

The crypto clustering challenge, aims to use your knowledge of Python and unsupervised learning (specifically K-means clustering) to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. The project also explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

---
## Part 1: Challenge Layout <a name="layout"></a>

1. Load and prepare the data.
2. Scale the data using StandardScaler.
3. Find the best value for k using the elbow method using the original scaled dataframe.
4. Cluster cryptocurrencies with K-means using the original scaled data.
5. Perform PCA to reduce the features to three principal components.
6. Find the best value for k using the PCA data.
7. Cluster cryptocurrencies with K-means using the PCA data.
8. Visualize and compare the results using hvPlot.

## Part 2: Results <a name="result"></a>
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

1.  Elbow curve for the original data.
   
<p align="center">
<img src="Images/crypto.jpeg" alt="crypto graphic" width="500" height="300"  >
</p>

2. Elbow curve for the PCA data.
   
<p align="center">
<img src="Images/crypto.jpeg" alt="crypto graphic" width="500" height="300"  >
</p>

3. Scatter plot of cryptocurrency clusters based on the original data.

<p align="center">
<img src="Images/crypto.jpeg" alt="crypto graphic" width="500" height="300"  >
</p>

4. Scatter plot of cryptocurrency clusters based on the PCA data.

<p align="center">
<img src="Images/crypto.jpeg" alt="crypto graphic" width="500" height="300"  >
</p>   

---
## Part 3: Conclusion <a name="conclusion"></a>   
In conclusion, this Tableau analysis provides a comprehensive overview of the trends and patterns in Citibike usage over a specified time period. Through the creation of interactive dashboards and visualizations, key insights have been extracted and presented, highlighting trends in user type, and usage, as well as trip patterns based on hours and weekdays. One noteworthy phenomenon observed from the overall analysis is the high usage of the Citibike service by residents of Jersey City, New Jersey, primarily for commuting purposes. This analysis serves as a valuable resource for anyone interested in understanding the usage of Citibike and exploring the data behind this popular bike-sharing service. I hope that this work will inspire further research and investigation into the data, and encourage others to build upon the insights presented here.
