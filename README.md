In this project we're working with exploratory data analysis of stock prices. The primary focus on this project is examining how bank stocks progressed
through the financial crisis all the way through November 20th, 2023. The significance of working within this dataset is the potential to predict how stocks
will further survive future crises within the market (mostly pertaining to recessions and downturns in the market). Stock brokers can use this data
to well manage the sales of their stocks in the case of the market facing any further crises.
The data can be found in Yahoo Finance as the key stocks are Amazon, Bank of America, CitiGroup, Goldman Sachs, JPMorgan Chase, and Morgan Stanley.

In the first task we found the data we needed using Yahoo Finance.
We find the stock data from Jan 1st, 2006 to November 20th 2023 for each of these banks.
Setting each bank in a different dataframe, creating a ticker symbol, and combining all of the data using the concat method.
Then finally we put all of the stock data together.

The second task is labeled as EDA which means exploratory data analysis.
Here we look at the max closing price for each stock, created a dataframe for
each of the returns and finding out the days the stocks had the best and worst returns over this time period.
Keeping in mind to understand why three of the stocks had the same worst return date and what was the potential cause for their simultaneous drop. 

In the third and final task of the notebook, we look into the visualization aspect of the data.
We perform several visualizations, first we graph the close column of the stocks dataframe (each stock) and combine the rest as a final result.
Then we create a pairplot for the entire dataframe using the returns. After that we code a histogram for each of the stocks and the final result being
all of the stocks together.

Lastly we calculate the 30 day moving averages using the windows method. Here we will compare the JP Morgan and Morgan Stanely, seeing their 30 Day 
Averages along with their closes. This is the final aspect of the project.

The jupyter notebook is available via this Github
