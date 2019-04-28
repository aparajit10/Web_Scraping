# Web_Scraping
Web scraping for ownership data for stocks  from Morningstar - 
This notebook uses selenium to scrape data from Morningstar's website in the following way - 
1) Search for the ticker of the stock that needs to be searched for. For example- 'AAPL'+'Morningstar'+'Ownership' on Google
2) Look for Morningstar.com in the search results 
3) click on the page and scrape the needed info
4) Append it to a dataframe
5) Create a CSV with this info
