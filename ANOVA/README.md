# Revenue Prediction with ANOVA and Linear Regression.

This project was completed as a part of the [Data Analyst nanodegree](https://openclassrooms.com/en/dashboard/paths) displayed by Openclassrooms. 


_At OpenClassrooms, the learning process is project-driven to ensure proficiency and get some hands-on experiences. 
The Data Analyst degree include 9 projects to get through all the fundamentals of the Data Analyst Role._

## 🎯 Purpose

Predict the revenue of customer's children in order to target potential future customers.
  

## 📒 Contents
  
This project includes the following steps:

  1) Collection & Exploration

Collect, Summarize and Discuss the relevance of the Data Collected for the Modeling.
Here is what we need to perform the modeling:

- World Income Distribution: This database is mainly composed of studies carried out at the national level for a good number of countries, and contains the income distributions of the populations concerned.
- Gini Index from the World Bank: https://data.worldbank.org/indicator/SI.POV.GINI
- Number of inhabitants of each country present in the data.

2) Features Engineering

Using the income generational mobility coefficient and the percentiles for each country, calculate the conditional probabilities between the class of parents and class of child. In other words, the probability of a child to be in a certain class of incomes depending in the class of income of his parents.

4) Data Preprocessing

Using conditional probabilities create a synthetic and representative dataset. 

5) Modelling 

Predict children's income using ANOVA-one way and Multiple Linear Regressions.
