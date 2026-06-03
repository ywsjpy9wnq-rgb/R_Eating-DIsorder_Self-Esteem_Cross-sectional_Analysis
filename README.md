# Overview
A hierarchical regression analysis examining whether the internal contingencies of self-esteem uniquely predict eating disorder behaviors beyond global self-esteem in a student sample (N = 138).
Data set built from Qualtrics survey tool, with additional analysis in Excel.

# Key Results
R² Step 1: 0.128 
R² Step 2: 0.267 
ΔR²: 0.139 

Model 1: EDEQ ~ RSES + DERS
Model 2: EDEQ ~ RSES + DERS + SCS
  Res.Df    RSS Df Sum of Sq      F    Pr(>F)    
1    135 118980                                  
2    134 100033  1     18947 25.381 1.492e-06 ***


# Final model:
Self-compassion was the only unique predictor (β = -0.40, p < .001), uniquely explaining 14% variance.

# Methods
- Hierarchical multiple regression
- Pearson correlations
- Cronbach's alpha for reliability
- Variance inflation factor (VIF) for collinearity
- Residual diagnostics (Q-Q plot, residuals vs fitted)
- Cook's distance for influential points

