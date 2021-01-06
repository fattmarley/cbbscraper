# cbbscraper
College Basketball web scraper that pulls predicted scores from Kenpom HaslaMetrics and BartTorvik as well as betting lines from Fanduel using Selenium


Creates pandas dataframes with plots showing predicted scores spreads and totals (Hasla table has space for 25 games by default but can be edited to be more or less at line 'HaslaF=pd.concat([Hasla, Hasla2], axis=1).iloc[0:x]' where x is the number of games wished to be displayed


Kenpom is a paid site and will require a login to be able to use the data, Hasla and Torvik are free. Kenpom login credentials can be edited in lines 20 and 22 (e.send_keys('username'), e.send_keys('password'))
