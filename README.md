# homelessness-clustering-analysis
Project Overview

This project explores patterns in homelessness service usage using machine learning clustering techniques. The goal was to group individuals based on how they interacted with different homelessness services and identify meaningful behavioral patterns. Understanding these patterns can help organizations better support individuals and improve resource allocation.
The dataset used in this project contains homelessness service usage data from Maricopa County, Arizona (2014–2018). Each record represents an individual and their usage of various homelessness services over time.

What This Project Does

Instead of manually analyzing thousands of records, clustering algorithms were used to automatically group individuals with similar service usage patterns. These groups help answer questions such as:
Are there different types of service users?
Do some individuals rely heavily on certain services?
Can we identify patterns that may indicate higher risk of returning to homelessness?

Algorithms Used

Three clustering algorithms were implemented:
1. KMeans — Creates a fixed number of clusters and works well for identifying balanced groupings
2. DBSCAN — Identifies clusters based on data density and detects outliers
3. BIRCH — Efficient for large datasets and creates hierarchical clusters

Key Findings

The algorithms produced different groupings, showing that homelessness service usage naturally forms multiple behavioral patterns. BIRCH was the fastest algorithm, while the elbow method suggested that meaningful clusters likely exist between 5 and 10 groups. Distance metric comparisons also showed that similarity measurement affects clustering outcomes.

Why This Matters

These findings can help policymakers and service providers better understand service usage trends, identify high-risk groups, and improve decision-making for homelessness support programs.
