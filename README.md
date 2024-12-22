## Machine Learning with Clustering: Traffic Signals Analysis

### Overview
This project demonstrates the application of clustering techniques—DBSCAN and K-Means—to analyze and visualize traffic signal data. The dataset was sourced from a PostgreSQL database and includes information such as latitude, longitude, intersection types, and other attributes.

The project showcases the use of Python, scikit-learn, and Matplotlib to perform spatial data clustering, providing insights into traffic signal distributions and patterns.

### Features
Database Connection: Establishes a connection to a PostgreSQL database and retrieves traffic signal data.
* DBSCAN Clustering:
Identifies clusters of traffic signals based on latitude and longitude.
Allows customization of eps and min_samples to optimize clustering performance.
Visualizes results using color-coded scatter plots.
* K-Means Clustering:
Applies K-Means clustering to categorize traffic signals into a specified number of clusters.
Visualizes cluster assignments and centroids.
Interactive Mapping: Combines geospatial data visualization with clustering results for enhanced interpretation.

### Requirements
* Python 3.8
Dependencies:
pandas
psycopg2
scikit-learn
matplotlib
