# Cryptocurrencies
## Overview
In this project, data from cryptocurrency csv was analyzed using Unsupervised Machine Learning Method KMeans Algorithm. Deliverables are below:
1. Pre-processed Data:
    - Data was filtered based on tradeability, working algorithm, and mined coins.
    - Null values were removed from data and unrelated columns, Coin Name, was removed.
    - String data types were converted to numeric data types.
    - Data was scaled using StandardScaler algorithm
2. Reduction Dimension:
    - Data was transformed using principal componenet analysis and features were transformed to 3 PCA
3. KMeans and PCA:
    - Elbow curve was used to determine the best K values
    - KMeans algorithm was used to group data based on 4 clusters
    - 3-D graph was created to show 4 cluster groups based on 3 PCA values
    - Table, using Hvplot, was created to display tradeable currencies
4. Coins Mined and Supply Visual:
    - Total coins mined and total coin supply data was scaled using MinMaxScaler 
    - Scatter plot showing relationship was created separating by KMeans cluster groups

### Purpose

### Resources
**Data retrieval:** [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

**Tools:** Python, PANDAS, SciKit-Learn, KMeans Algorithm, PCA Algorithm, StandardScaler, MinMaxScaler, Hvplot, Jupyter Notebook
