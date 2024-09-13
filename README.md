# Post_Grad_Multivariate_Analysis

This project investigates the difference between mean oral and facial temperatures. 

The data is loaded and the two key metrics are plotted showing a **clear positive correlation**. The plot also indicates the fact that the facial temperature is on average 2 degrees cooler than the facial temperature.

Oral Temperature values are positively skewed, while facial temperature values are more normally distributed. Oral Temperature **outliers are removed to ensure data normality** for later analysis.

A number of hierarchical clustering algorithms were run on the facial data with 'average' linking proving to be the most suitable approach. This approach suggests there are 3 distinct clustrers in the facial data. 

A k-means lcustering algorithm is also run on the data. The optimum number of clusters, 4, is found through the use of the 'elbow plot'. A k-means algorithm with k=4 is run on the data that is reduced by Principal Component Analysis. When these clusters were plotted against PC1 and PC2 the clusters were very discriminatory. The k-means clustering algorithm was prefferred in this instance to the Hierarchichal approach due to its enhanced cluster separations.

Linear and Quadratic Discriminat Analysis models are fit on the data. Models performance are compared with the best model (LDA) having its decision boundary plotted. The plot shows a strong performance.

Principal Component Analysis is performed on the data, with the first **3 Principal Components capturing the majority of the cumulative data variance**. The principal component scores are displayed to show the depreciating nature of component variance. 

Principal Componenent Regression is researched and described before an analysis is run. The model returns an **R-Squared value of 0.707** showing it **explains a significant amount of the variability** in the data. 
