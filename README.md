### Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset). 

### Goals of the project

The goal of the project is to predict the execution of how well the users are performing the set of exercises using all the predictor variables available.

### Approach

We will perform the following steps

1. Loading the data. We will load the data into Training and test data sets. 
2. Exploratory data analysis. We perform some exploratory data analysis on the training data set. This will help us get an idea of how many measurements are available and the quality of the measurements. We will try see see if there are any predictors we can easily eliminate by looking at the overview
3. Data Clean up. We will clean up the data based on the preliminary data analysis. Typically this is to eliminate badly collected data
4. Fitting a few models. We need to make some good choices on determining possible models to fit. If we fit too many models one of them is bound to fit just by the law of probabilities. The course advises us to use the test data set only once
5. Evaluate the models. Once the model performs well on the training data set we will run it only once against the test data set
6. Run the models against the coursers test dataset. We will try to predict the 20 results for the coursera test data
7. Load the test results into coursera for the project submission 