# Overview
The purpose of this project is to create an unsupervised learning model to group cryptocurrency data for presentation to a company that seeks to offer a cryptocurrency portfolio.

# Results
By drawing upon a cryptocurrency database, the data was cleaned, preprocessed, and applied to an unsupervised learning model with the following results:  
![results](https://github.com/pmercado625/Cryptocurrencies/blob/main/images/Elbow.png?raw=true)
![results](https://github.com/pmercado625/Cryptocurrencies/blob/main/images/ComponentReduction.png?raw=true)
![results](https://github.com/pmercado625/Cryptocurrencies/blob/main/images/MinedVSSupply.png?raw=true) </br>
The first processing was done to clean the data from the any irrelevant information. PCA was used in order to separate the variables into 3 principle components. Afterwards, the K means technique was used in conjunction with the elbow curve in order to identify the optimal number of clusters that should be looked for. Once the optimal number of clusters was found (in this case, 4), a 3D scatter plot was made via plotly express to visualize the 4 types of customers one could deduce from the data. Lastly, the data was scaled/prepared once more in order to create a graph of the various cryptocurrencies based on the amount of coins availabe (supply) and the amount of coins that have already been mined.
# Summary
The analysis that was conducted on the cryptocurrency database can be further examined based upon the particular clusters of the various cryptocurrencies. From this, a business may be able to choose which customers they may specifically would want to reach out to via their cryptocurrency portfolio choices.
