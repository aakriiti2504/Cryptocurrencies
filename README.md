# Cryptocurrencies

## Overview 
My childhood best friend Martha and I always dreamt about changing the world. When she gets the chance to pitch an investment in cryptocurrencies to her firm, Acoountability and Accounting, I jump into the chance to help out. After all we both think that changing the world is what cryptocurrency is all about. As both of us know that the popularity of bitcoin has caused a price jump, making it unaffordable to many new investors. However there are many more cryptocurrencies available at more affordable prices. Martha has a dataset of cryptocurrencies and can analyze it in any way she wants. Its my job to help Martha discover trends that will convince her firm to invest in new cryptocurrencies. This is also give us an insight into Unsupervised Machine Learning.


## Background

I start my converstaion with Martha by going over the part of machine learning I am most familiar with, Supervised Learning.
#### Supervised Learning - 
Supervised learning is fairly simple: We use it when we know what we're looking for or what our output should be. Two of the most popular techniques are classification and regression. For example, if we want to see how Bitcoin performs over time, or if we want to figure out what kinds of coins a user is most likely to buy, we use supervised learning. However, we use unsupervised learning when we don't yet know the question we're asking of the data. In other words, we just want to figure out if there is anything at all the data can tell us. In supervised learning, first a model is initiated, or a template for the algorithm is created. Then it will analyze the data and attempt to learn patterns, which is also called fitting and training. After the data has been fit and trained, it will then make predictions. In supervised learning, the input data already has a paired outcome, which is plugged in to train the model to predict outcomes in new datasets. For example, we want to build a model that, when given unfamiliar data, can accurately predict the outcomes.

However, we decide that we will be needing Unsupervised Learning since it is the best way forward for your dataset because you are looking for any groupings, trends, or other information that could help you pitch cryptocurrencies to her firm.
#### Unsupervised Learning - 
In unsupervised learning, there are two key differences from the above approach:

- There are no paired inputs and outcomes.
- The model uses a whole dataset as input.
Unsupervised learning is used in one of the following two ways:

##### 1.  Transform the data to create an intuitive representation for analysis or to use in another machine learning model; or
We use transformations when we need to take raw data and make it easier to understand. Transformations also can help prepare data so that it can be used for other machine learning algorithms.

For example, if you had cable TV viewer data, it might contain location, viewing duration, and viewer churn and retention during commercials and after programs ended. Transformations can reduce the dimensional representation, which simply means we'll be decreasing the number of features used for the model or analysis. After doing so, the data can either be processed for use in other algorithms or narrowed down so it can be viewed in 2D.
##### 2.  Cluster or determine patterns in a grouping of data, rather than to predict a classification.
We use clustering algorithms to group similar objects into clusters. For example, if a cable service wants to group those with similar viewing habits, we would use a clustering algorithm.


For example, imagine a store owner is planning to stock up on back-to-school supplies. The owner's challenges are selecting from a wide range of school supplies, devoting considerable space to the inventory, and maintaining a fast inventory turnover rate, from stocking to selling.

The owner wants to predict the best time to start selling school supplies so staff can make room for the next big items to sell. The owner decides to focus on the previous year's data, which includes the number of items sold, when they were sold, and the area schools' start dates for 10, 20, and 30 days prior to the items' sell dates. If the owner notices that when customers come in to buy school supplies, they also purchase non-school items, giving other categories a bump in sales. There are a wide variety of products to offer different consumers, so the owner wants to know which consumers might buy more products and what items they might want to buy. We don't really know how to group the data, but we know that grouping the data will be instructive. We will need to factor in many data points, such as age, race, gender, location, and much more.

Unsupervised learning does not take in any pairing of input and outcomes from the data; it only looks at the data as a whole. This can cause some challenges when running the algorithm. Since we won't know the outcome it's predicting, we might not know that the result is correct. This can lead to issues where we're trying to decide if the model has provided any helpful information that we can use to make decisions in the real world. The only way to determine what an unsupervised algorithm did with the data is to go through it manually or create visualizations. Since there will be a manual aspect, unsupervised learning is great for when you want to explore the data.

## Tools used 
1. Scikit-learn library in Python 
2. Plotly library in Python that is a graphing library that makes interactive, publication-quality charts.
3. hvPlot visualization library in Python that uses HolovViews and Bokeh
4. Pandas library in Python used for Data Munging
5. Dataset used -  https://archive.ics.uci.edu/ml/datasets/iris
6. Jupyter Notebook 

## Steps for preparing Data
Martha and I open up the dataset to get started preprocessing it. Together, we will want to manage unnecessary columns, rows with null values, and mixed data types before turning your algorithm loose. Before moving data to our unsupervised algorithms, we will complete the following steps for preparing data:

##### 1. Data selection
Data selection entails making good choices about which data will be used. Consider what data is available, what data is missing, and what data can be removed. For example, say we have a dataset on city weather that consists of temperature, population, latitude and longitude, date, snowfall, and income. After looking through the columns, we can readily see that population and income data don't affect weather. We might also notice some rows are missing temperature data. In the data selection process, we would remove the population and income columns as well as any rows that don't record temperatures.
##### 2. Data processing
Data processing involves organizing the data by formatting, cleaning, and sampling it. In our dataset on city weather, if the date column has two different formats—mm-dd-yyyy (e.g., 01-23-1980) and month-data-year (e.g., jan-23-1980)—we would convert all dates to the same format.
##### 3. Data transformation
Data transformation entails transforming our data into a simpler format for storage and future use, such as a CSV, spreadsheet, or database file. Once our weather data is cleaned and processed, we would export the final version of the data as a CSV file for future analysis.

### Clustering and K Means Algorithm 
Clustering is exactly what we want from unsupervised learning, but exactly how can we determine the clusters? Martha knows she needs to group the cryptocurrency data, but she isn't sure how to determine the number of groups to create. One of the most popular ways to cluster is by using the K-means algorithm.
K-means is an unsupervised learning algorithm used to identify and solve clustering issues.

K represents how many clusters there will be. These clusters are then determined by the means of all the points that will belong to the cluster.

The K-means algorithm groups the data into K clusters, where belonging to a cluster is based on some similarity or distance measure to a centroid.

A centroid is a data point that is the arithmetic mean position of all the points on a cluster:
![data-18-3-2-1-five-clusters-with-centroid](https://user-images.githubusercontent.com/23488019/155605523-54d0009f-7499-4d81-bf29-183c888beedc.png)
The centroid is found by taking the mean of all the x values in a cluster, and the mean of all the y values in a cluster.
## Purpose 


## Result 


## Summary 
