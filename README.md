# Cryptocurrencies

## Overview of the Analysis

## Results

**K-Means - Eblow Curve**
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10. The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

![bokeh_plot](https://user-images.githubusercontent.com/58046234/163841393-4ff37bf9-436f-4ee1-9153-8aae760e18dc.png)

**Scatter Plots**
Both these scatter plots show the distribution and the four clusters of cryptocurrencies. We can identify the outliers like the unique cryptocurrency in the class #2.

*3-D Scatter Plot*

![newplot](https://user-images.githubusercontent.com/58046234/163842239-9f103a61-0ce0-4f95-8251-1c81d9b2410f.png)

This visualization was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

*2-D Scatter Plot*

![bokeh_plot (1)](https://user-images.githubusercontent.com/58046234/163842203-5d02e3aa-0a7f-4d75-9516-e99206ab6996.png)

This 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.


## Summary
We have identified the classification of 532 cryptocurrencies based on similarities of their features. Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.
