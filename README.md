Concrete Compressive Strength Prediction using Machine Learning

Concrete is one of the most important materials in Civil Engineering. Knowing the compressive strength of concrete is very important when constructing a building or a bridge. The Compressive Strength of Concrete is a highly nonlinear function of ingredients used in making it and their characteristics. Thus, using Machine Learning to predict the Strength could be useful in generating a combination of ingredients which result in high Strength.

Description and Project Overview This project will be based on a dataset obtained from the UCI Repository. The dataset consists of 1030 observations under 9 attributes. The attributes consist of 8 quantitative inputs and 1 quantitative output

Attribute information
Inputs
•	Cement
•	Blast Furnace Slag
•	Fly Ash
•	Water
•	Superplasticizer
•	Coarse Aggregate
•	Fine Aggregate
All above features measured in kg/$m^3$
•	Age (in days)
Output
•	Concrete Compressive Strength (Mpa)

 Modelling and Evaluation
•	Algorithms used
o	Linear regression
o	Lasso regression
o	Ridge regression
o	Decision Trees
o	Random Forests
•	Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.


CONCLUSION:
Analysed the Compressive Strength and used Machine Learning to Predict the Compressive Strength of Concrete. We have used Linear Regression and its variations, Decision Trees and Random Forests to make predictions and compared their performance. Random Forest Regressor has the lowest RMSE and is a good choice for this problem. Also, we can further improve the performance of the algorithm by tuning the hyperparameters by performing a grid search or random search.
The best model will be helpful for civil engineers in choosing the appropriate concrete for bridges, houses construction.
