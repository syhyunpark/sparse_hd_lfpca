# sparse_hd_lfpca
codes for a sparse high-dimensional longitudinal functional principal component analysis  

will be used for fitting a logistic regression measurement error model with a longitudinal high-dimensional covariate. 

we fit a logistic regression model for a binary outcome, with high-dimensional random effects as covariates. the high-dimensional random effects must be estimated from the observed longitudinal high-dimensional data. therefore the model essentially involves errors in covariates. We aim to improve parameter estimation accuracy by taking into account those errors. the model will be estimated under conditioning on sufficient statistics of the subject-specific random effects, hence the estimation is free of the error-prone covariates. to handle the high-correlation and high-dimensionality of the longitudinal random effects covariates, we employ longitudinal principal component analysis and penalized estimation by the smoothly clipped absolute deviation. to achieve stability in estimation, we apply majorizations on the first derivative of the conditional score functions.
