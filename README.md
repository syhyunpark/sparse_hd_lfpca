# sparse_hd_lfpca
codes for a sparse high-dimensional longitudinal functional principal component analysis  

for fitting a logistic regression measurement error model with a longitudinal high-dimensional covariate. 

We fit a logistic regression model for a binary outcome, that uses high-dimensional random effects as covariates. These random effects must be estimated from observed longitudinal high-dimensional data, therefore the model essentially involves errors in covariates. Our aim is to improve parameter estimation accuracy by taking into account those errors. The model is estimated under conditioning on sufficient statistics of the subject-specific random effects, hence estimation is free of the error-prone covariates. To handle the high-correlation and high-dimensionality of the longitudinal random effects covariates, we employ the longitudinal principal component analysis and a penalized estimation using the smoothly clipped absolute deviation. To achieve stability in estimation, we apply majorizations on the first derivative of the conditional score functions.
