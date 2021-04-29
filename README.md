# Cryptocurrencies

## Overview of the project 

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

- Preprocessing the database,
- Reducing the data dimension using Principal Component Analysis,
- Clustering cryptocurrencies using K-Means,
- Visualizing classification results with 2D and 3D scatter plots.


## Resources

- Data Source : [crypto_data](/crypto_data.csv)
- Software :Python , Anaconda Navigator , Conda , Jupyter Notebook.


## Results 

**- Deliverable 1**

By using the knowledge of Pandas, we preprocessed the dataset in order to perform PCA.
the DataFrame below perform the data cleaned and where we kept the : Algorithm, ProofType, TotalCoinsMined and the TotalCoinSupply

![crypto](/Resources/crypto_df1.PNG)

**- Deliverable 2**

By using the knowledge of how to apply the Principal Component Analysis (PCA) algorithm, we reduced the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

- The PCA algorithm reduces the dimensions of the X DataFrame down to three principal components as shown in the image below

![PCA](/Resources/PCA2.PNG)

**- Deliverable 3**

Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

**- Deliverable 4**


Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal components you created in Deliverable 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.


