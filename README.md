# Predict-Demand


1. mplement the nested time series cross validation strategy for grouped forecasting.
    1. User should provide the dataset, time column and the number of folds to generate
    2. For the given dataset, we will use **"day"** as a single time unit. This means you can split the data at day level
2. Write you code in sci-kit learn format. Refer to the [KFold CV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html) for inspiration. The class should work on pandas dataframes and a datetime column name.
3. Test your code with some samples.
4. Build a time series model on the dataset above and evaluate it using your cross validation method. Submit the notebook illustrating the model development.
