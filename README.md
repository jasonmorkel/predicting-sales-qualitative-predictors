# predicting-sales-qualitative-predictors
 Analyizing the effect that qualitative predictors have on sales.


Simple exercise using a R library to predict sales of baby car seats in 400 locations based on a qualitative predictor.

The Carseats data (ISLR librbary) includes qualitative predictors such as ShelveLoc, an indicator of the quality of the shelving location - that is, the space within a store in which the car seat is displayed - at each location. The predictor ShelveLoc takes on three possible values, Bad, Medium, and Good.

Using R, we fit a multiple regression model that includes some interation terms.

ShelveLocGood in the regression output is positive indicating that a good shelving position contributes to high sales (relative to bad shelving position).
