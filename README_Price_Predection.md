# hadi_eyad_gold_price_prediction

Defining the problem: 
the problem is not knowing the future price of gold, so our solution is giving a machine that predict the price of gold

Defining and exploring the data:
The data is the price of gold from the year 2008 until 2018
check the website to know more about the data of gold price and explore by yourself 
https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data

(Solution) Steps of the codes:
-First step we imported the various libraries, so we can work on the project depending on it
in using it's functions 

-Second step we have loaded the CSV data of gold price to a panda dataframe
  -Printing first 5 dataframe 
  -Printing last 5 dataframe
  -Count the whole number of coloumns and Rows

-Third step we get some basic information about the data, to be able 
 of checking the number of missing values in each colomns and rows

-Fourth step we printed the statistical values of the data to know the (count of data, avrage of date
 minmum of data, maximum of data, etc...)
 
 -Fifth step we did correlation between postive and negative correlations to know the constrast
  and similarties between each data and element such as when gold increased also the silver increased
  with it, we also found few coloumns is postivly correlated to each other and other are negativaly 
  correlated

-Sixth we did the process of checking the distribution of the gold price and we found majority
 of the values lie on the range of 120 then
 
 -Seventh we splitted the columns and dropped the date on it and we stored the gold price value
 in y
 
 -Eigth after we splitted the columns we splitted the data set into training data and data test 
  using the strain test split function

-Ningth we trained the random forest regressor model using the fit function and we predicted our X test
 values 

-Tenth we squered the error values to see where we didn't have the predicted data accuratly like
 the actual real data
 
(Concluion) Last step is considers as the conclusion of this solution:
 -eleventh we did a graph where it compare the Actual values and the predicted ones in a plot
and we found out the the predection was actually close the real values, 

(Analysis) This what we saw from the conclusion
so the predection is not
completely accurate but approximately accurate and close to the actual values

