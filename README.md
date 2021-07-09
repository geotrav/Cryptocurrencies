# Cryptocurrencies

### Purpose of project

The project is designed to give a high overview of the cryptocurrencies in the market.  Cryptocurrency data from traded currencies is preprocessed for import into an unsupervised machine learning process.  This process removed coins that aren't currently traded(mined), null data is present, and catergorical data was coverted to numberical data for anaylsis.  The traded cryptocurrencies are placed in three principal components (PCA) to reduce the dimensions.  These three pricipal components were then evaluated and placed in a machine learning KMeans cluster algorithm.  Using elbow curve plot 4 clusters(classes) were chosen for the Kmeans clustering.

### Results

The data is located in the jupyter notebook file located here:

[Crypto_clustering](/crypto_clustering.ipynb)

3D Plot of the three PC along the X,Y,Z axes and colored by clustering class are in the file.
A summary table of the coins, their class, Total supply, Total mined, algorithm, Proof Type and CoinName is also provided.
Finally a 2D scatter plot of the coins supply vs mined content is provided to show the growth potential of the coins and how numerous the coins are in circulation vs their potential.