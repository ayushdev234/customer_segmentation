
# Customer Segmentation

Problem Statement:

The mall currently treats all customers alike, without recognizing the diverse needs and preferences of different customer groups. This lack of targeted approach results in suboptimal marketing strategies, inefficient resource allocation, and potentially poor customer satisfaction. The mall needs a way to understand its customer base better and tailor its services to different segments.

Solution Type Description:

The solution involves implementing a customer segmentation model using k-mean clustering and hierarichal clustering. This model will analyze the customer dataset and identify patterns and similarities among customers.
![Animated GIF](https://camo.githubusercontent.com/8543f7839329a64b88533176de6dfb44f69e90f628abe4c9ce50f156ccbc0593/68747470733a2f2f736f75726369666963636f6e73756c74696e672e636f2e756b2f77702d636f6e74656e742f75706c6f6164732f696d61676531392e676966)



## Dependencies
* Python 2.7 or Python >3.4
* pandas
* numpy
* scipy
* scikit-learn
* matplotlib
* seaborn
* jupyter notebook
## Dataset
| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|--------------------|------------------------|
| 1          | Male   | 19  | 15                 | 39                     |
| 2          | Male   | 21  | 15                 | 81                     |
| 3          | Female | 20  | 16                 | 6                      |
| 4          | Female | 23  | 16                 | 77                     |
| 5          | Female | 31  | 17                 | 40                     |
| 6          | Female | 22  | 17                 | 76                     |




..
..
.....
## Screenshots

![App Screenshot](screenshots/Screenshot%20(215).png)
![App Screenshot](screenshots/Screenshot%20(217).png)
![App Screenshot](screenshots/Screenshot%20(218).png)



## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Run the code given in ipython notebook `Cust_segmentation_online_retail.ipynb`


## Features

## K-Means Clustering:

- **Centroid-Based:** K-Means relies on centroids to form clusters.

- **Data Partitioning:** It categorizes data into K clusters based on proximity to centroids.

- **Scalability:** Efficient and scalable, suitable for large datasets.

- **Assumes Spherical Clusters:** Assumes clusters are spherical and equally sized.

## Hierarchical Clustering:

- **Cluster Hierarchy:** Builds a cluster hierarchy via merging or splitting.

- **Agglomerative/Divisive:** Can be agglomerative (bottom-up) or divisive (top-down).

- **No Predefined K:** Doesn't require specifying the number of clusters beforehand.

- **Sensitive to Noise and Outliers:** Prone to sensitivity with noise and outliers.

- **Computational Intensity:** Can be computationally intensive, especially for large datasets, considering all pairwise distances.

