# Yelp-Dataset-Review-Rating-Prediction 
### See FinalReport.pdf for detailed description.

 Oversampled minority classes using SMOTE to produce class-balanced data.

 Performed text cleaning and implemented bag-of-words embedding with tf-idf score to generate text matrix in Python.

 Analyzed conditional regression plots to derive new features in differentiating ratings using NumPy, Pandas and Matplotlib.

 Incorporated the derived dense features with sparse text matrix via stacking two Logistic Regression models.

 Performed 5-fold Cross Validation for tuning parameters and improved the MSE score from 2.064 (baseline) to 0.826.

 Experimented Latent Factor Model and Bi-Long Short Term Memory networks with GloVe embeddings on the text data, which performed the best in accuracy, improving from 0.453 (baseline) to 0.674.
