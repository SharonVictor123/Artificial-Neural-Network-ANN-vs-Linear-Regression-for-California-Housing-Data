OVERVIEW

This assignment assigned Artificial Neural Network (ANN) and Linear Regression models to predict house prices using the California Housing dataset. Their performance was to be compared, and their suitability for this regression task was to be evaluated.

Data Processing

Investigated the statistics and features of the dataset.
Appropriately dealt with outliers and missing values.
Divide the dataset into sets for testing and training.

Model Implementation

Linear Regression Model:
Served as a training set.
Based on the testing set, made predictions.
R2 Score and Mean Squared Error (MSE) were used for evaluation.
Artificial Neural Network (ANN): 
TensorFlow and Keras were used to create a basic ANN.
Used the training set to teach the ANN.
Predicted the testing set's housing prices.
Assessed using regression metrics identical to those for linear regression.


Findings

Metrics for Model Performance:
Linear Regression:
R2 Score: 0.5757877060324508
MSE: 0.5558915986952444
ANN: 
R2 Score: 0.784840100011837
MSE: 0.2819474647019028
Visualizations: Scatter plots contrasting the two models' actual and predicted values.
A visual representation of the ANN architecture.

Analysis and Insights

With a higher R2 Score and a lower MSE than linear regression, the ANN performed better.
[Insights from predicted vs. actual comparison] were shown visually.
If relationships were primarily linear, linear regression performed fairly well.
ANN architecture optimization, data preprocessing, and managing interpretability vs. complexity trade-offs were among the difficulties.

Conclusion

In conclusion, the ANN outperformed the other in terms of prediction, most likely because of its ability to recognize intricate non-linear relationships.
For simpler linear relationships, linear regression may be sufficient despite being more straightforward and interpretable.
Regression tasks require careful consideration of model complexity, interpretability, and data preprocessing.

GitHub Repository Link
SharonVictor123/Artificial-Neural-Network-ANN-vs-Linear-Regression-for-California-Housing-Data (github.com) 
