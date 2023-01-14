# CustomerSegmentation
This project is focuses on performing customer segmentation on a group of mall customers. I have used KMeans Unsupervised Learning machine learning algorithm to fund Univariate and Bivariate clusters. Once these clusters are identified, I have provided observations(Insights) on what the target cluster should be.
## Univariate and Bivariate analysis:
- I performed both, Univariate and Bivariate analysis to gain insights on the data.
- The correlation between annual income, age, and spending score was calculated. It is observed that the annual income and age are negatively correlated, and so are spending score and age.
- These observations are important when it comes to the content of the campaigns, the focus areas should be deteremined based on the age, their income and other such factors.
## Clustering:
- Algorithm: KMeans Unsupervised Learning ML algorithm
- First, I have created clusters based on the income.
Used elbow method to find the ideal number of clusters, that's 3 here.
For using the elbow method, I first calculated the intertia scores, and plotted them.
- For learning more about the relation between age, income and spending score, I calculated the mean age, mean annual income, and mean spending score for each cluster. 
- It can be observed that the mean annual income of the first cluster is very high, and high explains the high spending score.
- The second cluster had the highest mean age, and also the lowest average income. This falls in line with the observation from the heatmap.
- For Bivariate clustering, I have created Spending and Income cluster. Like in case of Univariate clustering, I used elbow method to find the number of clusters, 5 here.
- Observations:
  - The ideal cluster would be cluster 1. Because it has customers with high annual income and high spending score. This is the cluster that a company can target for sales. The focus items can be expensive watches, adgets, etc.
  - Cluster 2 can be young adults (based on the avg age) with less income, but make big purchases once in a while. The campaign for this group will be focused on items that are maybe trendy 
