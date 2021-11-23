![](https://img.shields.io/github/followers/alokthakur93?label=Follow%40alokthakur93&style=social)
![](https://img.shields.io/github/forks/alokthakur93/Customer-Personality-Analysis-Clustering-?label=Fork&style=social)
![](https://img.shields.io/github/stars/alokthakur93/Customer-Personality-Analysis-Clustering-?style=social)
![](https://img.shields.io/github/watchers/alokthakur93/Customer-Personality-Analysis-Clustering-?style=social)
![](https://img.shields.io/github/issues/alokthakur93/Customer-Personality-Analysis-Clustering-)
![](https://img.shields.io/github/repo-size/alokthakur93/Customer-Personality-Analysis-Clustering-)
![](https://img.shields.io/github/languages/code-size/alokthakur93/Customer-Personality-Analysis-Clustering-)

# Customer Personality Analysis

## What is Customer Personality Analysis ?

* Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.
* Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.


## Project Overview :
* Performed an unsupervised clustering of data on the customer's records from a groceries firm's database.
* Calculated the optimal number of clusters using elbow curve and silhouette score.
* Built a K-means model using optimal number of clusters and evaluated the model and analyzed the clusters formed.
* Summarized the clusters by profiling customers according to their family structures and income/spending. This can be used in planning better marketing strategies.

## Business Problem/Objective:
* Need to perform clustering to summarize customer segments.

## Data Cleansing and Pre-processing:
 Used following data cleansing and pre-processing techniques:
 1. Imputing missing values
 2. Encoding categorical variables
 3. Feature creation
 4. Feature selection.
 

## Performing Clustering:
Includes following steps:
1. Finding optimal number of clusters using Elbow curve.
![](https://raw.githubusercontent.com/alokthakur93/Customer-Personality-Analysis-Clustering-/main/Image/1.PNG)
2. Using 4 clusters as it can be observed from above graph.
3. Data distribution among 4 clusters:
![](https://raw.githubusercontent.com/alokthakur93/Customer-Personality-Analysis-Clustering-/main/Image/2.PNG)
4. Plotting Clusters based on Income and Spent:
![](https://raw.githubusercontent.com/alokthakur93/Customer-Personality-Analysis-Clustering-/main/Image/3.PNG)

**Income vs  spending plot shows the clusters pattern**
* group 1: high spending & low income  
* group 2: high spending & high income
* group 3: high spending & average income
* group 4: low spending & low income 


## Profiling the Clusters:
**CLuster 1 characteristics:**
- They are definitely a parent
- At max there are 5 members in the family and at least 2
- Majority of them have teenager at home
- Relatively older
- A lower-income group

**Cluster 2 characteristics:**
- Are definitely not a parent
- At max there are only 2 members in the family
- A slight majority of couple over single people
- Span all ages
- A high income group

**Cluster 3 characteristics:**
- Are definitely a parent
- At max have 4 members in family and at least 2
- Most have teenager at home
- Relatively older

**Cluster 4 characteristics:**
- The majority of these people are parents
- At max there are 3 members in family
- They majorly have one kid
- Relatively younger

## Conclusion:
In this project, I performed unsupervised clustering. 
I performed K-means clustering and used Elbow curve or Scree-plot to determine the value of K .
I came up with 4 clusters and further used them in profiling customers in clusters according to their family structures and income/spending. 
This can be used in planning better marketing strategies. 
 

 