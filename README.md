### First of all, thank you to ESPN.com and LeBron James for this project :)

#### During the Data Preparation phase: 
I got the numbers from ESPN.com by web scraping, using the request library, which LeBron James had scored at all times. Since this data I get is year-year, I defined quite a few functions to edit the date column and make it workable. In addition to this, I have defined a function for this in order to look at the in-game and out-game performance. 

#### In the Analysis and Plots phase:
I showed that the data I have is workable with simple but functional numerical analyzes. In the graphics part, I visualized the data I have according to various categories with libraries such as plotly, matplotlib and seaborn. 

#### In the Machine Learning phase:
I determined the dependent variable (y) as the scored points and defined 11 different independent variables (X). I preferred the Random Forest Regression model because there will be many nodes and trees because some of the correlations between the independent variables are too much and some are too little. As a result of the regression, you can see the metrics in the notebook. In addition, I used the ready-made methods in sciktlearn's metrics module in the cross-validation part.
