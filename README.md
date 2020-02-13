# Machine_Learning
This repository presents exciting projects using machine learning or interesting theoretical aspects.

## Model Selection

### Akaike information criterion (AIC) and Mallow’s C_p

The Akaike information criterion is an estimator of out-of-sample prediction error and thereby relative quality of statistical models for a given set of data. Given a collection of models for the data, AIC estimates the quality of each model, relative to each of the other models. 

<img src="http://latex2png.com/pngs/31faedcfbf64f3ec747f36abbc65628a.png" width="200"/>

Mallow’s <img src="http://latex2png.com/pngs/9f3d4296f92bcac8fd4935bc1a06ddbb.png" width="20"/> is a technique for model selection in regression. The <img src="http://latex2png.com/pngs/9f3d4296f92bcac8fd4935bc1a06ddbb.png" width="20"/> statistic is defined as a criteria to assess fits when models with different numbers of parameters are being compared.

<img src="http://latex2png.com/pngs/6b722798834f0df647104489ee2ab89d.png" width="200"/>

#### Task

Regression model is

<img src="http://latex2png.com/pngs/6a16c6466cb7d4ff8c0fc4c38339ca6c.png" width="150"/>

and <img src="http://latex2png.com/pngs/a585fca649d15ba28f30dc4b15455a2d.png" width="10"/> is dictributed normally: <img src="http://latex2png.com/pngs/cdc9a61937624354c56bfcb0061a33b9.png" width="100"/> is known.

Prove that the model with highest Akaike information criterion is the model with smallest Mallow's <img src="http://latex2png.com/pngs/9f3d4296f92bcac8fd4935bc1a06ddbb.png" width="20"/>

## Equivalence of Neural Networks with Different Activation Functions

A two-layer network function of the form:

<img src="http://latex2png.com/pngs/863465539102c17d6cdc8501748d4670.png" width="400"/>

in which the nonlinear activation functions are logistic sigmoid functions. There exists an equivalent network, which computes exactly the same function, but with hidden unit activation function given by hyperbolic tangent <img src="http://latex2png.com/pngs/2e3607a9d9d4b906dfceffb10c250bf2.png" width="60"/>


## Clustering

* Evaluation clustering performance using two clustering metrics: `silhouette score` and `adjusted mutual information`.
* Finding the best number of clusters using bootstrap.
* Evaluation variance of the metric and construction normal 95% confidence intervals.
