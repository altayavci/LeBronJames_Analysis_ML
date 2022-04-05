## First of all, thank you to ESPN.com and LeBron James for this project :)

### During the Data Preparation phase: 
I got the data from ESPN.com by web scraping, using the request library, which LeBron James' stats of at all-time. Since this data I get is year-year, date format did not fit the proper datetime format.So I defined quite a few functions to edit the date column and make it workable. In addition to this, I have defined a function for this in order to look at the in-game and out-game performance. 

### In the Analysis and Plots phase:
I showed that the data workable with simple but functional numerical analyzes (mean PTS per season etc.). In the plots part, I visualized the data I have according to various categories with libraries such as plotly, matplotlib and seaborn. Plotly plots on Readme_Plots.md

### In the Machine Learning phase:
I determined the dependent variable (y) as the scored points and defined 11 different independent variables (X). I preffered the Random Forest Regression model because there will be many nodes and therefore trees. The reason for this is that the dependence between the dependent variable and the independent variables is more in some and less in others. In addition, the correlation between independent variables also differs a lot. For example, when we compare the effect of time and assists on points scored in the 2011-2012 season in January 2011, and the effect of turnovers and assists on points scored in the 2013-14 season in March 2014, we see that the results can be very different.. As a result of the regression, you can see the metrics in the notebook. In addition, I used the ready-made methods in sciktlearn's metrics module in the cross-validation part.
