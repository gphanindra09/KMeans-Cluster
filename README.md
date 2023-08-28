# KMeans-Cluster


#import the numpy, matlot, pandas libery's
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt


Name:G.Phanindra
Roll No:20X01A6702
Branch:lV year cse(data science)
College:Narsimha Reddy Engineering College
Project Title : Analysis and prediction of "mall_Customers.csv" of american mall markets called as phonix mall to find out how many customers are visited to a particular shop.on the basis of this prediction of annual income verses spending scores
Disclimer: In this particular dataset we assume annual income has a centroid and spending score from the range 1 to 100 called as datanodes of the cluster
problem statement:The american finance market as per the gdp of 2011 "phonics_trilliuns mall as in the first range out of 5.The owner of the mall wants to be exact which particular shop or product search in diferent kind of clusters in entire mall
As a data science engineer predict the futuristic Finanacial market for upcomming gdp ratebased on no of clusters
The client wants tleast top 5 clusters(shops)
#import the numpy, matlot, pandas libery's
#Read the dataset take variable name called "dataset" only.
## <THE ELBOW METHOD>
#from sklearn used "sklearn.cluster" attribute and import KMeans
#Take a distance from from centroid to cluster point with WrapsColumnExpression.
# Assume you have 10 cluster and iterate the for up to range 10 with iterater kmeans++.
# Fit the model if value comes too samlla in range.

#For clustering in wcss ,inertia is adding / appending is required.(kmeans.inertia_)#defalut usecase.
#Plot the poarticular graph along with the wcss and your range which you taken as input variable.
#Add title "The Elbow Method".
#Lable x variable as "No of Customers".
#Lable y variable as "WCSS".
#Plot the graph using plt.show().
![image](https://github.com/phani12-gp/KMeans-Cluster/assets/123863815/77aeaed2-9901-4a33-b5a7-68517f234d5a)
![image](https://github.com/phani12-gp/KMeans-Cluster/assets/123863815/da8c8f8f-107b-496f-95b3-bbce3b4a38c1)
Conclusion: According to the model basics prediction using ml algorithm KMeans Clustering we found that cluster 1 which consist red color is the highest cluster which attach more than 50 data nodes.
Reference:The model building algorithm develop for all kinds of clusteration values the yellow spots represent centroids which is msx to max only 5
