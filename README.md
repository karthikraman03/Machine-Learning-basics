KNN BASISCS:

k-NN performs much better if all of the data have the same scale
k-NN works well with a small number of input variables (p), but struggles when the number of inputs is very large
In high dimensions, points that may be similar may have very large distances. All points will be far away from each other and our intuition for distances in simple 2 and 3-dimensional spaces breaks down.This might feel unintuitive at first, but this general problem is called the “Curse of Dimensionality“.
KNN does not learn any model.
There are many distance measures to choose from to match the structure of your input data.
Eucledian and Manhattan distance are most widely used algorithm for distance metrics.
Both Euclidean and Manhattan distances are used in case of continuous variables, whereas hamming distance is used in case of categorical variable.
Its classification performance depends on choosing the optimal number of neighbors (k), which is different from one data sample to another.
In KNN we can select the k values. The values should be an odd values like [1,3,5] to avoid even classifiers.
The multi classifiers system uses the odd numbers for the k parameter for two reasons:
  1) to increase the speed of the algorithm by avoiding the even classifiers; 
  2) to avoid the chance of two different classes having the same number of votes.
Rescale your data, such as using normalization, when using KNN.
We can use k-NN for regression problems and classification problems. 
k-NN algorithm can be used for imputing missing value of both categorical and continuous variables.
KD-trees are a specific data structure for efficiently representing our data. In particular, KD-trees helps organize and partition the data points based on specific conditions.
When KNN is used for regression problems the prediction is based on the mean or the median of the K-most similar instances.
When KNN is used for classification, the output can be calculated as the class with the highest frequency from the K-most similar instances. Each instance in essence votes for their class and the class with the most votes is taken as the prediction.
