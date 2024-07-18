# Customer Segmentation Using K-Means Clustering

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [K-Means Clustering](#k-means-clustering)
7. [Results](#results)

## Introduction
Customer segmentation involves dividing customers into groups based on similarities to tailor marketing efforts effectively. This project uses K-Means clustering to segment customers based on annual income and spending score.

## Project Overview
- **Objective:** Segment customers based on spending behavior based on annual income
- **Features:** Data preprocessing, exploratory data analysis, K-Means clustering, results

## Dataset
- **Source:** https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
- **Description:** This dataset contains customer data with features such as customer ID, age, gender, annual income and spending score.

## Data Preprocessing
- Handling missing values
- Handling duplicate values

## Exploratory Data Analysis
- Summary statistics
- Data visualization using histograms, box plots, and scatter plots to identify patterns

## K-Means Clustering
- Determine the no of clusters using the Elbow method
- Applying the K-Means algorithm to segment customers
- Iteratively assigning data points to clusters and updating centroids until convergence

## Results
- 5 groups of customers were identified:
    1.   **Light blue** - low income and low spending score  
    2.   **Dark blue** - high income and low spending score  
    3.   **Purple** - medium income and medium spending score  
    4.   **Green** - low income and high spending score  
    5.   **Yellow** - high income and high spending score  
