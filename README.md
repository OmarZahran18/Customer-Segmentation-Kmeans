# Customer Segmentation Using K-Means Clustering

This project performs customer segmentation on a dataset using K-Means clustering to group customers based on their Annual Income and Spending Score.

## Objective

- Segment customers into distinct groups to help businesses understand different customer profiles and tailor marketing strategies accordingly.

## Steps

1. **Data Preprocessing**  
   - Selected features: `Annual Income (k$)` and `Spending Score (1-100)`
   - Scaled features using StandardScaler for better clustering.

2. **Finding Optimal Clusters**  
   - Used the Elbow Method to determine the best number of clusters by plotting WCSS (Within-Cluster Sum of Squares).

3. **Applying K-Means**  
   - Ran K-Means clustering with the optimal number of clusters.
   - Visualized clusters with different colors and centroids.

## Tools & Libraries

- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

## Insights

- The dataset was successfully segmented into meaningful clusters.
- Businesses can target each cluster with tailored offers based on income and spending behavior.

## Author

[Omar Zahran](https://www.linkedin.com/in/omarzahran22/)
