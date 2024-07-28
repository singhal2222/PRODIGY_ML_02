# PRODIGY_ML_02
Customer Segmentation using K-means Clustering
This project is part of the Prodigy InfoTech internship in the Machine Learning domain. The task involves implementing a K-means clustering algorithm to group customers of a retail store based on their purchase history.

Project Overview
The goal of this project is to group customers into different segments based on their purchase history. The clustering will help the retail store understand their customer base better, allowing for targeted marketing and personalized customer experiences.

Dataset
For demonstration purposes, we used a generated dataset with the following key features:

CustomerID
AnnualIncome
SpendingScore (1-100)
However, you can replace this with your own dataset containing similar customer attributes.

Project Structure
The project consists of the following files:

customer_data.csv: Sample dataset with customer features.
customer_segmentation.ipynb: Jupyter notebook containing the code for data preprocessing, clustering, and visualization.
Implementation
Data Preprocessing
Loading the Data: The dataset is loaded into a pandas DataFrame.
Handling Missing Values: Missing values in the features are handled by filling them with the mean value of the respective columns.
Feature Scaling: The features are scaled using StandardScaler to ensure they contribute equally to the clustering process.
Clustering
The K-means clustering algorithm is applied to the preprocessed data. The optimal number of clusters is determined using the Elbow method.

Visualization
The resulting clusters are visualized using a scatter plot, with different colors representing different clusters. This helps in understanding the distribution of customers based on their annual income and spending score.

Results
The clustering algorithm successfully grouped the customers into distinct segments based on their purchase history. The visualizations provide clear insights into the characteristics of each customer segment.

How to Run
Clone this repository.
Place your dataset (if different from the sample dataset) in the project directory.
Open customer_segmentation.ipynb in Jupyter Notebook or Google Colab.
Run all the cells to see the results.
Visualization
A scatter plot is used to visualize the clusters. The plot shows the distribution of customers based on their annual income and spending score, with different colors representing different clusters.

Future Work
Future improvements can include:

Incorporating additional features such as age, gender, and purchase frequency for more detailed customer segmentation.
Exploring other clustering algorithms like DBSCAN or hierarchical clustering.
Implementing dimensionality reduction techniques like PCA for better visualization of high-dimensional data.
Acknowledgements
Prodigy InfoTech for the internship opportunity.
