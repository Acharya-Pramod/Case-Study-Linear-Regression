The aim is to use exploratory data analysis (EDA) and regression to predict alcohol levels in wine with a model that's as accurate as possible.

We'll try a univariate analysis (one involving a single explanatory variable) as well as a multivariate one (involving multiple explanatory variables), and we'll iterate together towards a decent model by the end of the notebook. The main thing is for you to see how regression analysis looks in Python and jupyter, and to get some practice implementing this analysis.

Throughout this case study, questions will be asked in the markdown cells. Try to answer these yourself in a simple text file when they come up. Most of the time, the answers will become clear as you progress through the notebook. Some of the answers may require a little research with Google and other basic resources available to every data scientist.

For this notebook, we're going to use the red wine dataset, wineQualityReds.csv. Make sure it's downloaded and sitting in your working directory. This is a very common dataset for practicing regression analysis and is actually freely available on Kaggle, here.

You're pretty familiar with the data science pipeline at this point. This project will have the following structure: 1. Sourcing and loading

Import relevant libraries
Load the data
Exploring the data
Choosing a dependent variable
2. Cleaning, transforming, and visualizing

Visualizing correlations
3. Modeling

Train/Test split
Making a Linear regression model: your first model
Making a Linear regression model: your second model: Ordinary Least Squares (OLS)
Making a Linear regression model: your third model: multiple linear regression
Making a Linear regression model: your fourth model: avoiding redundancy
4. Evaluating and concluding
