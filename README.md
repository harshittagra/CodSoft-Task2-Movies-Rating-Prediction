# movie-rating-prediction
Predicted the imbd rating of the movie using machine learning algorithm 

# Pre Processing
1) Removed the null value rows from the data
2) As you can see it is Uncleaned Data so Cleaned it using Various technique.
3) Convert the column having string value to numberical value

# Data Visualization:
1) Ploted the Count plot for years , Top 10 Directors , Top 10 Directors,Top 10 Directors
2) Ploted the pair plot to check relation between features.
3) Plotted Histplots  for Rating, Votes, Duration

# Result

| Model                  	          | Accuracy 	|
|------------------------    	      |----------	|
| Linear Regression     	          | 93.52    	|
| Ridge Regression          	      | 93.52     |
| lasso Regression                 	| 35.8    	|
| Elastic Net Regression           	| 73.0    	|
| Support Vector Regression         | 92.1    	|
| Random Forest Regressor           | 94.4    	|
| K-Nearest NeighborsRegression     | 91.4    	|
| Decision Tree Regressor           | 90.1    	|



# We observed that Random Forest Regressor performs well among all of them with accuracy of 94.38 % indicating its robustness.
