# Logistic Regression from Scratch on Car Purchase Data

This project involved recreating the logistic regression algorithm from scratch based on the methodology presented in the YouTube tutorial ["How to implement Logistic Regression from scratch with Python"](https://www.youtube.com/watch?v=YYEJ_GUguHw). The recreated logistic regression model was then applied to ["Cars - Purchase Decision Dataset"](https://www.kaggle.com/datasets/gabrielsantello/cars-purchase-decision-dataset). 

## Dataset

This dataset contains 1000 records of car purchase records, which includes ID, Gender, Age, Annual Salary and Purchase Decision columns. The data from Gender, Age and Annual Salary columns will be used to fit the data to logistic regression function to predict future purchasing decisions based on these metrics. 

Dataset link: https://www.kaggle.com/datasets/gabrielsantello/cars-purchase-decision-dataset

## Additional analysis

In this notebook I added several minor additions to the initial analysis performed on the video from [AssemblyAI Youtube channel](https://www.youtube.com/@AssemblyAI).

- Added an exploratory data analysis for the Cars purchase decision dataset.
- Created a version of sigmoid function that prevents underflow/overflow.
- Applied an oversampling technique to balance the classified instances.
- Compared logistic regression models that used regular and normalized data for training the model.

