# 2018 NFL Rushing Leaders

## Project Info

I am taking a deep analysis of the 2018 National Football League's Rushing Leaders using data science techniques to get a better understanding of the running aspect of the game of football. 

In addition, I wanted to learn Python and dive into the world of data science.

## Missing Data & Distribution Plots

I look for missing data and take a look at:

- Number of players who scored touchdowns
- Rushing leaders per team
- Age of rushing leaders
- Top 10 quarterbacks that lead in rushing yards
- Distribution of total rushing yards

Take a look - [Missing Data & Distribution Plots](https://github.com/jrosario22/2018NFLRushingLeaders/blob/master/MissingDataDistributionPlots.ipynb)

## Outliers & Multi-Variable Plots

When analysizing the relationship between age and total yards, I found some outlier that needed a closer look. I also examine the relationships between:

- Touchdowns and Total yards
- Yards per attempt and Total yards

Take a look - [Outliers & Multi-Variable Plots](https://github.com/jrosario22/2018NFLRushingLeaders/blob/master/OutliersMultiVariablePlots.ipynb)

## Linear Regression

My linear regression model would predict touchdowns based on the total yards a player would run

Take a look - [Linear Regression](https://github.com/jrosario22/2018NFLRushingLeaders/blob/master/LinearRegression.ipynb)

## Decision Tree

I generated a decision tree regressor to predict the number of yards a player would rush for. I split my data into training and testing data(80/20 split respectively).

Take a look - [Decision Tree](https://github.com/jrosario22/2018NFLRushingLeaders/blob/master/LinearRegression.ipynb)

## K-Nearest Neighbors

Running the same training and testing data as my decision tree to predict total yards, I generated a k-nearest neighbor regressor of max depth of 3 in attempt to catch sight of any changes.

Take a look - [K-Nearest Neighbors](https://github.com/jrosario22/2018NFLRushingLeaders/blob/master/K-NearestNeighbors.ipynb)

## Decision Tree Classifier

For my last analysis, I ran a decision tree classifier to predict a players position.

Take a look - [Decision Tree Classifier](https://github.com/jrosario22/2018NFLRushingLeaders/blob/master/DecisionTreeClassifier.ipynb)
