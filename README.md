# Clustering Project

## Problem Statement
Customer segmentation is a process by which customers are divided based on shared characteristics—such as demographics or behaviors—so that a marketing team or sales team can communicate with them more effectively. There are various segmentation variables that should be carefully considered when clustering customers to ensure customer satisfaction. These characteristics are not exclusive to all businesses and must be customized for different industries. These characteristics often include age, individual demographics, social status, income level, job type, education level, etc.  

In this project, customer information and purchase data from a shopping center are used. The dataset includes features such as customer ID, age, gender, income level, and purchase score. Customer segmentation is performed based on age and income level using three clustering algorithms:
1. **K-Means Clustering** - A partition-based method that assigns each data point to the nearest centroid.
2. **Hierarchical Clustering (Agglomerative)** - A bottom-up approach that merges similar data points iteratively.
3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** - A density-based approach that finds core samples and expands clusters based on density reachability.

## Dataset
The project uses a dataset named `Customer.csv`, which contains customer-related data. The dataset is preprocessed before applying clustering algorithms. The dataset is provided as an **Excel file**, and the implementation is in an **IPython Notebook (.ipynb)**.

## Dependencies
To run this project, install the required Python libraries:
```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Steps to Run the Notebook
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repo-name
   ```
3. Open Jupyter Notebook:
   ```sh
   jupyter notebook Clustering.ipynb
   ```
4. Run the cells sequentially to see the clustering methods applied to the dataset.

## Results & Visualization
- **Elbow method** is used to determine the optimal number of clusters in K-Means.
- **Dendrograms** visualize hierarchical clustering.
- **DBSCAN** identifies noise points and clusters based on density.
- The results include scatter plots and cluster distributions for interpretation.