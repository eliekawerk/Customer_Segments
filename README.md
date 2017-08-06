# Customer Segments

This repo contains jupyter notebooks for a data science clustering project. We aim at building a model that can segment the customers of an online retailer.

The code in the notebooks was executed using python 2.7; the following python libraries were used throughout the project:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn

[Data-Dictionary](Data-Dictionary.pdf) contains the description for each feature present in the Customer Segments dataset.

## Project Structure

- **Section 1**: [Data Wranling](1_Data_Wrangling.ipynb)
- **Section 2**: [Dimensionality Reduction](2_Dimensionality_Reduction.ipynb)
- **Section 3**: [Principal Component Analysis](3_Principal_Component_Analysis.ipynb)
- **Section 4**: [Cluster Analysis](4_Cluster_Analysis.ipynb)

## Project Context
Our client is an online retailer based in the UK. They sell all-occasion gifts, and many of their customers are wholesalers.

* Most of their customers are from the UK, but they have a small percent of customers from other countries.
* They want to create groups of these international customers based on their previous purchase patterns.
* Their goal is to provide more tailored services and improve the way they market to these international customers.

## Our Role
The retailer has hired us to help them create customer clusters, a.k.a "customer segments," through a data-driven approach.

* They've provided us a dataset of past purchase data at the transaction level.
* Our task is to build a clustering model using that dataset.
* Our clustering model should factor in both **aggregate sales patterns** and **specific items purchased**.


## Current Solution

Currently, the retailer simply groups their international customers by country. As you'll see in the project, this is quite inefficient because:

1. There's a large number of countries (which kinda defeats the purpose of creating groups).
2. Some countries have very few customers.
3. This approach treats large and small customers the same, regardless of their purchase patterns.

## Problem Specifics

It's always helpful to explicitly lay out the problem specifics before starting.

```
Deliverable: Clusters for customers
Machine learning task: Clustering
Target variable: N/A (Unsupervised learning)
Win condition: N/A (Subjective results)
```
