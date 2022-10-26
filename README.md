# Module_10_Assignment
## Cryptocurreny Investments

This assignment is to do cluster analysis by using PCA model compared with using cryptocurrency original data under the same condition of using K-Mean model and Z-score data transformation.

1. The first thing to do is importing data from csv file and preparing data in a clear and clean format.

2. Next step to do is calculating data under Z-score, we will use Z-score numbers to do clustering analysis.

3. The first part of clustering is by using Z-score dataframe with K-Means method to find the best of k value to decide how many clusters we need. After I plot the eblow curve and found that the optimal k value is 3. Then I was doing a scatter plot with 3 different clusters in one graph.

4. The second part is using PCA model with K-Mean method to find the best k value, dataframe is from Z-score data that I have prepared from the beginning. After applying PCA model with Z-score dataframe, I create a new dataframe to store PCA value. Then I start finding optimal k value with new dataframe. From the new elbow curve, the optimal value is 3 as well. After getting my k value, I use it to do a scatter plot with 3 different clusters in one graph.

Since I use 2 different ways to graph 2 different scatter plots and 2 different elbow curves, I combine them together into one page which is easier for me to make a comparison and analyze the difference.

Generally, PCA model shows a clear scatter plot with each datapoint are categorized in their own area, which is more concentrate and organized. Obviously, PCA model is using the theory of reduced factors which only collect significant data we need for analysis, that way can illustrate a clear scatter plot with each point being well organized and categorized.
