# Project-1

Sources: 
  1) https://changeoracle.com/2023/01/31/renewables-are-growing-but-is-it-enough-to-stop-climate-change/ -- Used in order to extract data surrounding global renewable energy capacity which was manually estimated and entered as a list (IN [124]) and then added to the dataframe "filtered_df" (IN [125])
  2) Xpert learning assistant -- IN [120] Used to help resolve persisting errors related to converting close price dictionary to a dataframe: df = pd.DataFrame(list(close_prices.items()), columns=['Date', f'{ticker} Close Price']) and to merge all of the dataframe on the 'Date' index: pd.concat(stock_data.values(), axis=1)
