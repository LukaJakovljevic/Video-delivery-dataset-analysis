# Video-delivery-dataset-analysis
P2P (peer to peer) and CDN (Content Delivery Network) downloads measurement and analysis.

# Video delivery dataset analysis

### Dataset Information

This dataset is measuring the data downloaded through **P2P** (peer to peer) and through the **CDN** (Content Delivery Network) by the viewers. 




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
