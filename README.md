# Implementation-of-K-Means-Clustering-for-Customer-Segmentation

## AIM:
To write a program to implement the K Means Clustering for Customer Segmentation.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Load the customer dataset and select relevant features for segmentation.

2. Initialize the number of clusters K and randomly assign initial centroids.

3. Assign each customer data point to the nearest centroid based on distance.

4. Recalculate centroids and repeat the process until clusters stabilize.
## Program:
```
/*
Program to implement the K Means Clustering for Customer Segmentation.
Developed by: H. MOHAMMED IRFAN
RegisterNumber: 212225230179 
*/
```
```
/*
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
data = pd.read_csv("Mail_Customers.csv")
X = data[['Annual Income (k$)', 'Spending Score (1-100)']]
print(data.head())
kmeans = KMeans(n_clusters=5, random_state=42)
y_kmeans = kmeans.fit_predict(X)


data['Cluster'] = y_kmeans

print("\nClustered Data:")
print(data.head())


plt.figure()
plt.scatter(X[y_kmeans == 0]['Annual Income (k$)'], 
            X[y_kmeans == 0]['Spending Score (1-100)'], label='Cluster 0')

plt.scatter(X[y_kmeans == 1]['Annual Income (k$)'], 
            X[y_kmeans == 1]['Spending Score (1-100)'], label='Cluster 1')

plt.scatter(X[y_kmeans == 2]['Annual Income (k$)'], 
            X[y_kmeans == 2]['Spending Score (1-100)'], label='Cluster 2')

plt.scatter(X[y_kmeans == 3]['Annual Income (k$)'], 
            X[y_kmeans == 3]['Spending Score (1-100)'], label='Cluster 3')

plt.scatter(X[y_kmeans == 4]['Annual Income (k$)'], 
            X[y_kmeans == 4]['Spending Score (1-100)'], label='Cluster 4')

plt.scatter(kmeans.cluster_centers_[:,0], 
            kmeans.cluster_centers_[:,1], 
            s=200, label='Centroids')

plt.title("Customer Segmentation using K-Means")
plt.xlabel("Annual Income (k$)")
plt.ylabel("Spending Score (1-100)")
plt.legend()
plt.show()
Developed by: 
RegisterNumber:  
*/
```
## Output:
![ex10/Screenshot 2026-03-11 133138.png](<Screenshot 2026-03-11 133138.png>)
![ex10/Screenshot 2026-03-11 133153.png](<Screenshot 2026-03-11 133153.png>)
![ex10/Screenshot 2026-03-11 133203.png](<Screenshot 2026-03-11 133203.png>)



## Result:
Thus the program to implement the K Means Clustering for Customer Segmentation is written and verified using python programming.
