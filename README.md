# Post-Graduate Multivariate Analysis

**Objective**

This analysis aims to explore the relationship between ***mean oral*** and ***mean facial temperatures*** focusing on identifying patterns, temperature ranges, and significant clusters in the data. 
A combination of ***clustering algorithms, discriminant analysis***, and ***regression techniques*** are used to identify patterns and derive insights from the data.

**Data Overview**

The data is loaded and a plot is generated between the two key metrics showing a ***clear positive correlation*** with facial temperature on average ***2 degrees cooler*** than the oral temperature.

**Data Distribution & Outliers**

Oral Temperature values are positively skewed, while facial temperature values follow a normal distribution. 
Oral Temperature ***outliers are removed to ensure data normality*** for later analysis.

**Clustering**

***Hierarchical Clustering***

Several Hierarchical clustering algorithms were tested on the facial data. 'Average' linking proved to be the most suitable approach. This approach suggests there are 3 distinct clusters in the facial data. 

***K-Means Clustering***

A k-means clustering algorithm was also applied with the 'elbow plot' indicating the optimum number of clusters as 4. A k-means algorithm with k=4 is run on the data that is reduced by Principal Component Analysis. When these clusters were plotted against PC1 and PC2 the clusters were very discriminatory. The k-means clustering algorithm was preferred in this instance to the Hierarchichal approach due to its enhanced cluster separations.

**Discriminant Analysis**

Linear and Quadratic Discriminant Analysis models were fit to the data. The models performance are compared, with the best model (LDA) having its decision boundary plotted. The plot shows a ***strong classification performance***.

**Principal Component Analysis**

Principal Component Analysis is performed on the data, with the first ***3 Principal Components capturing the majority of the cumulative data variance***. The principal component scores are displayed to show the diminishing contribution of component variance. 

**Principal Component Regression**

Principal Component Regression is researched and described before an analysis is run. The model returns an ***R-Squared value of 0.707*** showing it ***explains a significant amount of the variability*** in the data. 
