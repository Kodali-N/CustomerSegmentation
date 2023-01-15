# Customer Segmentation
This project is focuses on performing customer segmentation on a group of mall customers. I have used KMeans Unsupervised Learning algorithm to find Univariate and Bivariate clusters. Once these clusters are identified, I have provided observations(Insights) on what the target cluster should be.
## Univariate and Bivariate analysis:
- I performed both, Univariate and Bivariate analysis to gain insights on the data.
- The correlation between annual income, age, and spending score was calculated. It is observed that the annual income and age are negatively correlated, and so are spending score and age.
- These observations are important when it comes to the content of the campaigns, the focus areas should be deteremined based on the age, their income and other such factors.
## Clustering:
- Algorithm: KMeans Unsupervised Learning algorithm
- First, I have created clusters based on the income.
- Used elbow method to find the ideal number of clusters, that's 3 here.
![univar_elbow](https://user-images.githubusercontent.com/86663030/212472376-13a92e9f-f2a2-4915-9cf8-31e52302ac45.png)
- For using the elbow method, I first calculated the intertia scores, and plotted them.
- For learning more about the relation between age, income and spending score, I calculated the mean age, mean annual income, and mean spending score for each cluster.
<img src="https://user-images.githubusercontent.com/86663030/212472457-71017aa3-ab99-410b-97d0-bbc73a26e4b9.jpeg" width="450" height="150">

- It can be observed that the mean annual income of the first cluster is very high, and high explains the high spending score.
- The second cluster had the highest mean age, and also the lowest average income. This falls in line with the observation from the heatmap.
- For Bivariate clustering, I have created Spending and Income cluster. Like in case of Univariate clustering, I used elbow method to find the number of clusters, 5 here.
- ![bivar_elbow](https://user-images.githubusercontent.com/86663030/212472395-12b5f5ec-1ae6-4be1-ba6d-92e28ccf0fd5.png)
<img src="https://user-images.githubusercontent.com/86663030/212472440-947fcc4d-5974-40f4-aa4d-aae27c2230aa.jpeg" width="600" height="500">
<img src="https://user-images.githubusercontent.com/86663030/212472466-5fec5212-e5ef-4f51-b288-2b2cf4d40a92.jpeg" width="450" height="200">
- Observations:
  - The ideal cluster would be cluster 1. Because it has customers with high annual income and high spending score. This is the cluster that a company can target for sales. The focus items can be expensive watches, adgets, etc.
  - Cluster 2 can be young adults (based on the avg age) with less income, but make big purchases once in a while. The campaign for this group will be focused on items that are maybe trendy 
