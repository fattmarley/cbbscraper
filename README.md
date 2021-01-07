# cbbscraper
College Basketball web scraper that pulls predicted scores from Kenpom HaslaMetrics and BartTorvik as well as betting lines from Fanduel using Selenium


Creates pandas dataframes and plots which are saved in a pdf file and emailed to chosen addresses



Kenpom is a paid site and will require a login to be able to use the data, Hasla and Torvik are free. Kenpom login credentials can be edited in lines 20 and 22 (e.send_keys('username'), e.send_keys('password'))
