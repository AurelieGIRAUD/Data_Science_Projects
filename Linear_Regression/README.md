# Multiple Linear Regression applied to a Marketing Case Study

### ✅ Business Case

In this project, we are trying to predict sales revenues based on the budget invested into social media - _Youtube, Facebook and some newspapers_, using a multiple linear regression. The main focus of this project is to display **how to validate the key assumptions of such a model**. 

### 📉 Dataset

The dataset can be found on [Kaggle](https://www.kaggle.com/fayejavad/marketing-linear-multiple-regression).
It describes the advertising experiment between Social Media Budget and Sales (in Thousands $ ) and hold 200 experiments.


### 📒 Context

_Most firms that think they want advanced AI/ML really just need linear regression on cleaned-up data._ [Robin Hanson]


There are four principal assumptions which support using a linear regression model for the purpose of inference or prediction, which we need to verify in order to validate the model.

#### 1. Linearity
We must have a linear relationship between our features and responses. This is required for our estimator and predictions to be unbiased.
If you try to fit a linear model to data which is nonlinearly or nonadditive, your predictions are likely to be seriously in error, especially when you extrapolate beyond the range of the sample data. 

#### 2. Normality
Residuals must be Normally distributed (i.e variance tend to 1 and mean tend to zero). This is necessary for a range of statistical tests, such as the t-test. We can relax this assumption in large samples due to the central limit theorem.

#### 3. Homoscedasticity
Means that the residuals have constant variance no matter the level of the dependent variable.

#### 4. Independence
Residuals must be totally free of autocorrelation.


#### ... And Multicollinearity
For multiple linear regression, you also need to check the absence of multicollinearity. Multicollinearity refers to when two predictors (or more) are providing the same information about the response variable. 
