# CUSTOMER SEGMENTATION USING K-MEANS CLUSTERING
Customer segmentation is one of  the application of data mining which helps to segment the customers with similar patterns into similar clusters hence, making easier for the business to handle the large customer base. Clustering has been proven effective to implement customer segmentation. Clustering comes under unsupervised learning, having ability to find clusters over unlabelled dataset. There are a number of clustering algorithm over which like k-means, hierarchical clustering, DBSCAN clustering etc. 

## k-Means clustering
It is the simplest algorithm of clustering based on partitioning principle. The algorithm is sensitive to the initialization of the centroids position, the number of K (centroids) is calculated by elbow method, after calculation of K centroids by the terms of Euclidean distance data points are assigned to the closest centroid forming the cluster, after the cluster formation the barycentre’s are once again calculated by the means of the cluster and this process is repeated until there is no change in centroid position.

### Problem Statement: 
A retail store wants to understand its customer segments so that it can create a cutomized marketing plan for each of them.

### Goals:
- To customize market programs that will be suitable for each of its customer segments. 
- To also raise further market research questions as well as providing directions to finding the solutions.

### Dataset : 
[Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

### Work flow
- Data collection
- Data preprocessing
- Data visualization
- Feature scaling
- Feature normalization
- Optinum number of clusters using the WCSS(Within Clusters Sums of Squares) method
- K-means clustering
- Validating the clusters

### Libraries
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit Learn

### Data Visualization
#### Scatterplot between Annual Income (k$) and Spending Score (1-100)
![download (2)](https://user-images.githubusercontent.com/92667306/158186060-b6f0d38f-38e3-4bdf-96d3-51b78d405838.png)

### Finding the optinum number of clusters using the WCSS(Within Clusters Sums of Squares) method and then plotting the elbow graph
![download (3)](https://user-images.githubusercontent.com/92667306/158186879-a8313c18-9e80-4494-bdad-e0d88edd8001.png)

From the above graph one can see that from number of cluster = 4 to number of cluster = 5 there has been substantial decrease hence, I have chosen the K value for our dataset as 5.

### Visualizing all the clusters
![download (4)](https://user-images.githubusercontent.com/92667306/158187324-9cc06317-a6a4-4f50-ae77-ce209dccee68.png)

### Business Insights
The result of the analysis shows that the retail store customers can be group into 5 clusters or segments for targeted marketing.

- Cluster 1 (green): These are low income earning customers with high spending scores. I can assume that why this group of customers spend more at the retail store despite earning less is because they enjoy and are satisfied with the services rendered at the retail store.

- Cluster 2 (yellow): These are average income earners with average spending scores. They are cautious with their spending at the store.

- CLuster 3 (red): The customers in this group are high income earners and with high spending scores. They bring in profit. Discounts and other offers targeted at this group will increase their spending score and maximize profit.

- Cluster 4 (blue): Low income earners with low spending score. I can assume that this is so because people with low income will tend to purchase less item at the store.

- Cluster 5 (purple): This group of cutomers have a higher income but they do not spend more at the store. One of the assuption could be that they are not satisfied with the services rendered at the store. They are another ideal group to be targeted by the marketing team becuase they have the potential to bring in increased profit for the store.

