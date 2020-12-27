# Customer-segmentation

### This data set contains data for market basket analysis.

The data contains:

  Customer ID
  
  Unique ID assigned to the customer
  
  Gender
  
  Gender of the customer
  
  Age
  
  Age of the customer
  
  Annual Income
  
  Annual Income of the customee
  
  Spending Score
  
  Score assigned by the mall based on customer behavior and spending nature
  
  
   

### K Means Clustering Algorithm
 
1. Specify number of clusters K.
2. Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
3. Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.


### Elbow method

The Elbow method is a very popular technique and the idea is to run k-means clustering for a range of clusters k (let’s say from 1 to 10) and for each value, we are calculating the sum of squared distances from each point to its assigned center(distortions).

When the distortions are plotted and the plot looks like an arm then the “elbow”(the point of inflection on the curve) is the best value of k.

  

