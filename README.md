# PROJECT: Customer Segmentation with K-Means Clustering

## DESCRIPTION:
This project applies K-Means clustering for customer segmentation using the Mall Customers dataset. 
Customers are grouped based on Annual Income and Spending Score to help businesses understand customer behavior.

## DATASET COLUMNS:
- CustomerID: Unique customer ID
- Genre: Male/Female
- Age: Customer age
- Annual Income (k$): Annual income in thousands
- Spending Score (1–100): Customer spending score

## STEPS:
1. Import dataset and check for missing values
2. Visualize Annual Income vs Spending Score with scatter plot
3. Implement K-Means manually:
   - Initialize centroids randomly
   - Assign points to nearest centroid (Euclidean distance)
   - Update centroids until convergence
4. Encode categorical variables (Genre) using One-Hot Encoding
5. Apply Scikit-Learn’s KMeans for optimized clustering
6. Determine the optimal number of clusters (K) using:
   - Elbow Method (distortion vs K curve)
   - Silhouette Method (cluster quality measure)
7. Predict new customer cluster assignment

## RESULTS:
- Customers were segmented into 3 main groups:
  1. High Income, Low Spending
  2. Low Income, High Spending
  3. Balanced Income & Spending
- Elbow method suggested candidate K values
- Silhouette method validated cluster quality

## KEY LEARNINGS:
- How to implement K-Means from scratch
- How to use Scikit-Learn’s KMeans
- How to determine optimal cluster count
- Application of clustering in business (customer segmentation)

## REFERENCES:
- K-Means Clustering: https://en.wikipedia.org/wiki/K-means_clustering
- Elbow Method: https://en.wikipedia.org/wiki/Elbow_method_(clustering)
- Silhouette Method: https://en.wikipedia.org/wiki/Silhouette_(clustering)
