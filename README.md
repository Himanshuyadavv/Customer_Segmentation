# Customer_Segmentation
## Overview
Customer Segmentation involves breaking down a customer base into distinct groups based on various relevant factors like gender, age, interests, and spending habits. In the initial phase of our data science project, we'll embark on a journey of data exploration. This entails importing crucial packages necessary for analysis, followed by the meticulous examination of our dataset. By delving into the data, we aim to extract valuable insights essential for shaping our segmentation strategy.

Businesses employing customer segmentation recognize that each customer possesses unique needs, necessitating tailored marketing efforts for effective engagement. Their goal is to develop a nuanced understanding of their target audience, ensuring precision in their approach. By personalizing their strategies to cater to individual customer requirements, companies can unlock deeper insights into preferences and identify lucrative market segments. Armed with this knowledge, they can refine their marketing techniques, maximizing returns while mitigating investment risks.

![s5fnt55xnirfeyitsbor](https://github.com/Himanshuyadavv/Customer_Segmentation/assets/104669558/b08134ab-56e0-4eaa-9e85-4457e7b5d329)

## Algorithm
### K-Means Clustering:
The K-Means algorithm is an iterative approach designed to partition a dataset into K distinct, non-overlapping subgroups or clusters, with each data point exclusively belonging to one group. Its objective is to maximize the similarity within clusters while minimizing the dissimilarity between them. This optimization is achieved by assigning data points to clusters in a manner that minimizes the sum of squared distances between each point and its cluster's centroid. The result is cohesive clusters with minimal internal variation, facilitating the identification of underlying patterns in the data.

In our project, we leveraged K-Means Clustering to categorize spending activities based on age and annual income. This process involved the algorithm randomly selecting initial centroids from the dataset and iteratively updating them based on the Euclidean Distance to form clusters. Similar spending behaviors were grouped together, allowing for the visualization of distinct clusters representing different consumer segments. This iterative refinement process, akin to the k-Nearest Neighbors approach, enabled us to create meaningful clusters that capture the inherent structure of the data.

![WL1tIZ4](https://github.com/Himanshuyadavv/Customer_Segmentation/assets/104669558/23f278d7-6bc8-47a8-a573-3c709078dadd)

## Dataset
The dataset consists of following five features:

* CustomerID: Unique ID assigned to the customer

* Gender: Gender of the customer

* Age: Age of the customer

* Annual Income (k$): Annual Income of the customer

* Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.

## Clone Repository
Clone this Repository using,





