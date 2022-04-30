# Customer segregation for marketing strategy
<br>

___

Please refer to the ```Clustering.ipynb``` jupyter notebook for the complete code.

A detailed description is provided in this [medium article](https://medium.com/@saadjansari/customer-segmentation-for-marketing-strategy-tutorial-46db74237532)
____

#### Context
This data set (Customers.csv)is created only for the learning purpose of the customer segmentation concepts, also known as market basket analysis. I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.

#### Content
You are owing a supermarket mall and through membership cards, you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.
Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data. 
The data for this project is obtained from this [Kaggle page](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

#### Problem Statement
You own the mall and want to understand the customers and how they can be targeted so that the sense can be given to marketing team to plan strategy.

#### Acknowledgements
From Udemy's Machine Learning A-Z course

___


#### Proposed Solution
We aim to cluster customers and create customer personas to better describe the type of customers we have. To do so, we use KMeans clustering to find an optimal number of clusters. We can create personas by looking at the mean value of features within each cluster. Finally, we make marketing strategy recommendations.

#### Outline:
1. Import modules
2. Load Data
3. Early Visualization
4. Data Cleaning
5. Feature Standardization
6. KMeans Clustering
7. Feature Engineering
8. Analyzing Clusters
9. Customer Profiles
10. Marketing Strategy
___

