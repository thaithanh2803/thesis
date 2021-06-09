# Thesis

The goal of my paper is to examine the predictive relationship between a collection of potential variables and equity premium, and to compare the predictive performance of various non-linear methods.

In this paper, I examine the out-of-sample performance of monthly equity premium forecasts for the __S\&P500__. 

I conduct an analysis of non-linear methods for forecasting equity premium, including `neural network`, `principal component regression (PCR)`, `the combination of neural network and principal component analysis (PCANN)`, `Mallows model averaging (MMA)`, and `iterated combination method (IC)` and the results show that these methods can actually improve predictions. 

I start with the univariate predictive models using single hidden layer feed-forward neural network where each model is based on one of the 5 selected variables, __b/m__, __ntis__, __d/y__, __tbl__ and __e/p__. 

Next, I consider the multivariate models which incorporate information from all these 5 variables, including `PCR with maximum 3 principal components`, `neural network using first principal component as its input`, `MMA with 32 individual models`, and `iterated combination of all aforementioned models with historical average`.

The results indicate that single model over a long period is not sufficient and structural changes in the data play important role in analyzing predictability of a model. 
