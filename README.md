# Cryptocurrencies

## Purpose
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked me to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Research Process

- Using Pandas, we preprocessed a cryptocurrency dataset.
- Using the Principal Component Analysis (PCA) algorithm, we reduced the dimensions of a DataFrame we created to three principal components and place these dimensions in a new DataFrame.
- We created an Elbow Curve using hvPlot to find the best value for K from the pcs_df DataFrame created. 
- We then ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.
- We created a scatter plot with Plotly Express and hvplot, to visualize the distinct groups that correspond to the three principal components we created.
- Lastly, we created a table with all of the currently tradable cryptocurrencies using the hvplot.table() function.
