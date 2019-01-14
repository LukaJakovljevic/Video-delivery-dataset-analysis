# Video delivery dataset analysis

### Dataset Information

This dataset `data.csv` is measuring the data downloaded through **P2P** (peer to peer) and through the **CDN** (Content Delivery Network) by the viewers. 


### Content

Each data point has the following dimension, represented with 6 variables:

| Name | Description |
| -----| ----- | 
| #stream |  ID of each stream |
| isp |  Name of the Internet Service Provider |
| browser |  Browser name |
| connected |    Boolean value, true if the user is connected to the backend during his session |
| p2p | Data downloaded through P2P (peer to peer) |
| cdn | Data downloaded through CDN (Content Delivery Network) |


### Goal

The goal of this notebook is to explore the dataset and give recommendations as to where the service should be improved.


### Technologies used

* **Python** (version 3.7.0) - because the dataset is not too large to require some Big Data framework;
* **Jupyter notebook** (version 5.7.2) - because of the readability and explanation of the steps;
* **Pandas library** (version 0.23.4) - for data manipulation, analysis and plotting.


### Approach

1. Understanding the dataset in terms of columns and their values;
2. Visualizing which values affect connectivity to the backend;
3. How much data is sent in which stream and over which ISP/browser;
4. Visualizing correlation between ISP, browser, connectivity and bandwidth;
5. Trying to see if there are points where the service could be improved.
