# Cryptocurrencies

## Overview
The purpose of this project is to create a report that includes the cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Results:

### Preprocessing the Data for PCA:
Remove null values and unnecessary columns ,standardize the features.

![image](https://user-images.githubusercontent.com/120151872/235381298-cbdbe432-e46d-4e00-92f1-63309e399619.png)

### Reducing Data Dimensions Using PCA: 
Reduce the features to three primary components.

![image](https://user-images.githubusercontent.com/120151872/235381368-116cff4e-f311-4fcf-975d-6818cdec501d.png)

### Clustering Cryptocurrencies Using K-means:
Create an elbow curve using 'hvplot' to find the best value for 'K'. Then run the K-Means algorithm to predict the K clusters for the cryptocurrencies.

![image](https://user-images.githubusercontent.com/120151872/235381456-f6247f84-c977-44eb-955b-a8051f486d9a.png)

### Visualizing Cryptocurrencies Results:  
Create a scatter plots with Plotly Express and hvplot, to visualize the distinct groups that correspond to the three principal components.

![image](https://user-images.githubusercontent.com/120151872/235381544-30fcbe57-3cab-40fd-86f5-d7ed35284cb6.png)

Create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

![image](https://user-images.githubusercontent.com/120151872/235381612-c2108694-3fd3-4704-ba80-64854d7ebeca.png)

Create a scatter plot to show the relationship between the "TotalCoinSupply" and "TotalCoinsMined" columns.

![image](https://user-images.githubusercontent.com/120151872/235381653-c17b0c3d-2102-486b-a9a3-7ed4548dbdcd.png)
