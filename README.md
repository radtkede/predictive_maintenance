# predictive_maintenance

PoC for predicting the condition of a oil pump

-> original data as csv export from big refinery in germany
-> first attempt using lstm for prediction

Results: RMSE of 15.023

Only problem is that there no information available on when the pump was shut down because of failure. So we took the performance as indicator of when the pump needs maintenance in this moment. Next to that we start collecting these information to get a better output variable one time in the future.
