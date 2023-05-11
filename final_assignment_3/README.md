## Machine Learning Assignment 3

In this assignment, you will used an unsupervised learning method to cluster. Choose any one of the following three options for completing the assignment: 

### [Option 1](https://github.com/visualizedata/ml/tree/master/final_assignment_3/option_1)

Work with the Amazon Fine Food Reviews dataset, consisting of 455,000 food reviews Amazon users left up to October 2012 **to create a recommendation engine for Amazon products**. [[Download Amazon.csv here](https://drive.google.com/open?id=0Bxpj6pLMNxkTMXBtRFAydXJPQ2s); must be logged into Google with your newschool.edu to access]

### [Option 2](https://github.com/visualizedata/ml/tree/master/final_assignment_3/option_2)

Work with a set of images of and metadata on ~400 works of fine art from museum collections and galleries **to cluster them on metadata and/or image characteristics**. 

### [Option 3](https://github.com/visualizedata/ml/tree/master/final_assignment_3/option_3)

Work with data on food contamination **to cluster incident descriptions into broader categories**. 

## For this assignment I embarked on Option 4

### Option 4

Work with data on TV Shows from IMDb **to cluster into more nuanced descriptions beyond genres**

My personal goal was to cluster the data to reveal different racial experiences, particuarly multiracial ones. Both my elbow plot and shillouete plot were not as helpful as hoped - the elbow plot remaining pretty smooth and flat into the 500s for n-cluster and the shillouete plot creating non-uniform jaggety shapes of varying widths. 

Preprocessing the data required taking creating a clean data frame void of any dashes or commas.

For the time given on the assignment, I settled on 34 for the number of clusters.

With the majority of my model data points clustering in:

Cluster 10: Interracial couples amongst a family dynamic setting
Cluster 17: Interracial couples misc group
Cluster 21: Interracial couples amongst a wider ensemble cast
Cluster 28: data points that did not have any identifying keywords like interracial 

*Though these clusters have some noise to them

With more time I would like to further investigate higher number of clusters, in the 500-1000 range, but due to the limited time and the length of processing time it woudl have taken, that exploration will have to wait for the future. 
