# Customer-Segmentaion-employing-Spark-MLlib
Customer Segmentation Using Spark MLlib

This project focuses on customer segmentation using advanced clustering techniques, leveraging Apache Spark's distributed machine learning library (Spark MLlib). The analysis is based on a real-world dataset from a hotel in Lisbon, Portugal, spanning 2015–2018. The dataset contains 83,590 entries across 31 features, including personal, behavioral, demographic, and geographic attributes.

By identifying distinct customer groups, the project aims to enhance decision-making for personalized marketing strategies, improve customer satisfaction, and optimize operational efficiency in the hospitality industry.

Objectives:

Perform Data Preprocessing: Ensure a clean and structured dataset for machine learning.
Implement Advanced Clustering Techniques: Apply K-Means and Gaussian Mixture Model (GMM) to identify customer segments.
Conduct Comprehensive Analysis: Gain insights into customer behavior and booking patterns.
Provide Actionable Recommendations: Enable targeted marketing strategies and improved service design.
Methodology:

Data Preprocessing:
Converted key variables (e.g., age) to suitable formats.
Removed unnecessary columns such as hashed identifiers.
Handled missing values by imputing the mean for numerical features.
Standardized and scaled data for clustering compatibility.
Exploratory Data Analysis (EDA):
Visualized numerical data distributions using histograms.
Analyzed booking patterns and correlations between key variables.
Examined demographic trends (e.g., nationality) with geospatial visualizations like choropleth maps.
Investigated customer preferences for special requests (e.g., room location, bed types).
Clustering Analysis:
K-Means Clustering:
Utilized the elbow method to determine the optimal number of clusters (k=6).
Analyzed cluster characteristics such as age, revenue, and booking behaviors.
Gaussian Mixture Model (GMM):
Performed soft clustering to account for overlapping customer segments.
Compared results with K-Means to identify consistent patterns.
Case Study on Retail Marketing:
Demonstrated how identified customer segments can guide personalized marketing campaigns.
Illustrated the impact of segmentation on improving revenue generation and customer engagement.
Results:

Identified key customer clusters with distinct characteristics, such as:
High-spending customers who prefer premium services.
Younger groups with minimal preferences for room attributes.
Older customers with specific preferences for quiet, elevator-accessible, and high-floor rooms.
Showcased actionable insights for optimizing booking strategies and service offerings.
Enhanced clustering effectiveness by comparing K-Means and GMM methodologies.
Technologies Used:

Framework: Apache Spark (PySpark, MLlib)
Visualization: Matplotlib, Seaborn, Plotly (for interactive geospatial maps)
Tools: Jupyter Notebook
Dataset Source: Lisbon hotel booking dataset (2015–2018)
Potential Applications:

Improve customer service and satisfaction through targeted offerings.
Optimize marketing campaigns based on customer behavior and preferences.
Enhance operational planning with data-driven insights into booking trends.
This project contributes to the field of customer segmentation by combining distributed computing with robust machine learning techniques. It provides practical insights and recommendations for businesses aiming to adopt data-driven strategies in customer-focused decision-making.

