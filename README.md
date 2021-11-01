# Frecuency and Severity Models with Xgboost and LightGBM for Pure Premium Calculation

From December 2020 to March 2021, the *Insurance Pricing Game* competition took place on the AIcrowd platform organised by Imperial College London.

I had the opportunity to participate, learning a lot about applying predictive modelling to actuarial pricing. 

In this document I show what was my best submission for the RMSE-based ranking between the pure premiums output from the participants' models and the actual claims from a hidden dataset. 

The most interesting point is the use of the *lightgbm* library in R, for the severity model. A recent library much faster than *xgboost* and in some cases with better results.

For more information on how the competition works visit web competition. 

**Link to competition:** 
https://www.aicrowd.com/challenges/insurance-pricing-game
