# NBA-MVP-prediction
An end-to-end ML project to predict the MVP winner for an NBA season. It involves Web Scraping, Data Cleaning and finally makes predictions using Linear Regression and Random Forest models 

### Part 1
Download the NBA data we need by using web scraping.  
To do the scraping, we will use python, with the selenium, beautifulsoup, pandas, and requests libraries. 
We will download the files using requests and selenium, then parse them with beautifulsoup and load them into pandas DataFrames.
Finally we will have csv files with all required datsets

### Part 2
Now we will do the data cleaning part. 
We'll combine our mvp, player, and team stats data using pandas.  
We will work through a lot of data cleaning, including using merge, map, fillna, and replace.  
We will also utilise matplotlib to explore the data.  
Finally we will have a clean DataFrame that we can use for running the machine learning model.

### Part 3
We will use machine learning to predict who will win MVP each year.  
We first prepare the data for machine learning and use a Ridge Regression model.  
Then define an error metric, backtest across most of the data set, and iterate on our predictors.  
We'll end by using a Random Forest model to detect non-linear relationships and make predictions.
