# sparse_hd_lfpca
codes for a sparse high-dimensional longitudinal functional principal component analysis  

for fitting a logistic regression measurement error model with a longitudinal high-dimensional covariate. 

We fit a logistic regression model for a binary outcome, using high-dimensional random effects as covariates. These random effects must be estimated from the observed longitudinal high-dimensional data, and therefore the model essentially involves errors in covariates. We aim to improve parameter estimation accuracy by taking into account those errors. The model will be estimated under conditioning on sufficient statistics of the subject-specific random effects, hence estimation is free of the error-prone covariates. To handle the high-correlation and high-dimensionality of the longitudinal random effects covariates, we employ the longitudinal principal component analysis and a penalized estimation using the smoothly clipped absolute deviation. To achieve stability in estimation, we apply majorizations on the first derivative of the conditional score functions.
