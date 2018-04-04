# Ames_ModelFitting

**Domain**<br/>
The domain of this dataset came from the Assessor's Office that describes 3970 properties that were sold between 2006 and 2010 in Ames, Iowa. The data contains 80 features (23 nominal, 23 ordinal, 14 discrete, and 20 continuous) that are used to describe each property.<br/>

**Problem Statement**<br/>
We wish to be able to predict the SalePrice of a property by using the other 79 features given to us. In this study we will be using supervised learning through regression models. We will use the train dataset to determine which machine learning model gives the best R-squared score and use it to predict the SalePrice of houses listed on the test dataset.<br/>

**Data sets and Input**<br/>
The 80 features can be found in the data_description.txt file on the website where the dataset was found. The Data set used is obtained from kaggle. The train and test set contain 1460 and 1459 instances respectively, while the test set is missing the target, SalePrice, in order for us to give a prediction.<br/>

**Solution Statement**<br/>
The solution to the problem is to apply a regression model such as linear model or decision tree.<br/>

**Benchmark**<br/>
A good benchmark for a regression problem is to use the mean.<br/>

**Performance Metric**<br/>
A good performance metric for a regression problem is to use the R-squared metric.<br/>
