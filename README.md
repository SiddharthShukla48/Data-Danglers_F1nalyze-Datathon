# Data-Danglers_F1nalyze-Datathon

Team Name --> Data Danglers
Team Members --> Siddharth Shukla AND Tanuj Tyagi 



Why we primarily choose Decision Tree Regressor -> beacuse it gave least RMSE which we got by using pycaret. (Pls check the notebook attached)

Preprocessed the data end endcoded with label encoder. We tried target encoder and got 1.29 RMSE on validation set without hyperparameter tuning but since test set didnt had target column so we coundnt use target encoding.

Adjusted some parameters of deceision tree regressor to get the least RMSE possible within out time limits.

Tried TabTransformers too but we are not able to get the results due to time and computation constrants.

