# ML-Regression-Project-Bike-Sharing-Demand-Prediction
Currently many big cities have adopted the use of rental bikes to improve mobility comfort. It is crucial to make the rental bikes accessible and available to the general public at the appropriate time since it reduces waiting. Eventually, maintaining a steady supply of rental bikes for the city emerges as a top priority. Predicting the number of bikes needed to maintain a steady supply of rental bikes at each hour's interval is essential.With the help of these bike sharing programmes, users can hire a bike from one spot and return it to another or the same location as needed. Bikes can be rented by members or on a need-basis. On the basis of previous usage patterns in connection to weather, time, and other data, we were tasked to anticipate the demand for bike sharing. Provided with the Bike Sharing dataset, it contained weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Project Execution

Understanding the dataset, performing some basic data inspection to verify the number of columns, comprehending data distribution, and examining the statistics for each variable.

Performing Exploratory Data Analysis to get maximum insights from the raw dataset as well as visualising the data to make these insights easily understandable to stakeholders. This included various Univariate, Bivariate and Multivariate analysis.

Data processing that includes taking care of missing values, outlier detection using box-plots and outlier removal using IQR and technique, multicolliniearity detection using collinearity heatmap and handling multicollinearity by calculating VIF for each feature.

Feature Engineering, which is creating new features, dropping the unnecessary ones, converting categprical features into numerical using Label encoding and getting new features from a multi-label categorical feature using One Hot Encoding and finally Feature Selection before model building.

Defining model prerequisits such as Train-Test split, Feature transformation, Feature Scaling and setting hyperparameters.

Experimenting with various ML algorithms and getting their evaluation scores and feature importances.

We experimented using simple Lasso Regression model,Ridge Regression model, ElasticNet, Random Forest, DecisionTreeRegresson XGBoost,GradientBoostingRegressor, ExtraTreeRegressor and AdaBoostRegressor model. We employed Hyperparameter Tuning using GridsearchCV on the tree based models.

We finally concluded the project with XGBoost giving the best model performance followed by  ExtraTreeRegressor and RandomForest.
