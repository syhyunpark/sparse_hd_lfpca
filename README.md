# sparse_hd_lfpca
codes for performing a sparse high-dimensional longitudinal functional principal component analysis  

these will be used for fitting a logistic regression measurement error model with a longitudinal high-dimensional covariate- 

We propose an estimation approach for a logistic regression model that uses high-dimensional random effects as covariates, which must be estimated from the observed longitudinal high-dimensional data. The model essentially in- volves errors in covariates, and we aim to improve parameter estimation accuracy by taking into account those errors. We estimate the model under conditioning on sufficient statistics of the subject-specific random effects, hence the estima- tion is free of the error-prone covariates. To handle the high-correlation and high-dimensionality of the longitudinal random effects covariates, we employ lon- gitudinal principal component analysis and penalized estimation by the smoothly clipped absolute deviation. To achieve stability in estimation, we apply majorizations on the first derivative of the conditional score functions.
