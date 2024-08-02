# Customer Segmentation

## Overview

This project uses KMeans clustering to segment customers based on their annual income and spending score.

## Dataset

- **File:** `Mall_Customers.csv`
- **Features:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## Steps

1. **Load Data:**
   - Load the dataset and select relevant columns.

2. **Determine Clusters:**
   - Use the Elbow Method to find the optimal number of clusters.

3. **Cluster Data:**
   - Apply KMeans clustering with 5 clusters and visualize the results.

## Results

- **Elbow Method Plot:** Helps find the optimal number of clusters.
- **Clustering Plot:** Shows customer groups and centroids.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Lamrotibsa/PRODIGY_ML_02.git

2. **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. **Run the Analysis:**

    Execute the provided Python script or notebook.
