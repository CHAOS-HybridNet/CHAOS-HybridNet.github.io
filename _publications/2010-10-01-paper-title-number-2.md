---
title: " Spatial Variable Prediction Problem Based on Co-Kriging
 and Its Derived Algorithms"

date: 2024-09

paperurl: 'http://academicpages.github.io/files/数维杯.pdf'

---

 The synergistic kriging algorithm is an algorithm that can use covariates to effectively
 estimate the main spatial variables when the sampling volume of the main spatial variables
 is insufficient. This paper mainly focuses on the use of the synergistic kriging algorithm
 in combination with other algorithms to reduce its computational difficulty and improve its
 estimation accuracy.
 For question 1, using Kriging Interpolation, the spatial variables of the F1-target are
 randomly sampled, and the Kriging Algorithm is applied to estimate the value of the unsampled
 points by using the value of the sampled points, and on the basis of which, several times of
 sampling with different sampling rates (1%-50%, with a step size of 1%) are carried out, to
 explore the relationship between the amount of sampling and the estimation error. It is found
 that when the sampling rate reaches 20%, the error begins to tend to remain at a low and stable
 value.
 Forquestion2, thecorrelationbetweenthecovariatesandtheF1-targetwasinvestigatedusing
 the data in Attachment 1. By combining the linear and non-linear correlations through a prelim
inary analysis using the Spearman correlation coefficient, it was found that F1-collaborative
variable1 had a relatively high correlation with the F1target, and this was then This view was
 further corroborated by Random Forest Regression Analysis.
 For Problem3, basedontheanalysisofProblem2, F1-collaborative-variable1 is mainly used
 for the analysis, and Collaborative Kriging Algorithm is used to estimate for the sampling
 points, andthesamemethodofmultiplerandomsamplingisadopted,whichisusedtoexplorethe
 relationship between the estimation error and the sampling rate. To further analyse the algorithm
 properties, the Co-Kriging algorithm is found to have significant accuracy by comparing with
 RFK model, Smooth Bivariate Spline Algorithm, InearNDInterpolator Algorithm, while
 the RFK model reduces the computational difficulty with better accuracy.
 For Problem 4, in the face of a very small effective sampling size (1.24%) and the problem
 of low correlation between covariates and the main variable, a combination of Random Forest
 and Kriging algorithms is used for estimation (RFK model), an algorithm that effectively solves
 the problem of the difficulty of calculating covariates for covariates that have low correlation,
 and at the same time ensures the accuracy of the estimation.
