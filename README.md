# Ames_Housing_SalePrice_Prediction

This project aims at predicting the sale price of the Ames_Housing raw data.
The link for the data set can be found at:
  [(https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)]

The data was modified by dealing with the outliers, missing values and the categorical data.

By using the ElasticNet regression model and using GridSearch approach, the final predicted values were found to be 10% off from the mean sales price.

Final Conclusion:
* 10% off is a reasonable error considering the real-estate price fluctuations.
* Inspite of considering nearly 274 featues, we still had an error of 10%. By using Lasso Regression, there is a possibility that the number
  of relevant features might come down and the predition model might have a better accuracy score
