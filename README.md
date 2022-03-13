# Analyzing Twitter's influence in the Stock Market

This group project started with the choice of 2 datasets: Nasdaq Historical Prices and Tweets for some of the biggest companies on the stock market (Apple, Microsoft, Tesla and Amazon).

Both datasets were merged into a combined schema that was then converted into a data warehouse.

The tables for the DW were created in a Jupyter notebook, connected to a mySQL database, with psycopg2. 

Data manipulation was done with pandas. The dataset info was then loaded into the data warehouse, using psycopg2 as well.

In the end, we could not come to a definite conclusion in regards to the initial premise of the project, as there are a lot of external factors that influence the price of a stock.
