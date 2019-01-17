# IEX-API-Stock-Data-Finder
Uses the IEX API to collect information about a stock. The information is pulled from the IEX website, and 
returned in a pandas dataframe format.

*Make sure that Python's requests library is installed.

1) Type in the ticker for the stock to get minute data for today: "FB"
2) If you want daily data over a range of time, put a comma after the ticker followed by: 5y,2y,ytd,6m,3m,1m,1d (ytd is year to date) 
For example: "FB, 5y"
3) If you want minute data, write the date in YYYYMMDD format :"FB, 20190116"
4) If you specify a date range, all minute data between those dates will be given: "FB,20190105,20190110"
