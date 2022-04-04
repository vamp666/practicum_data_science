# Determining the optimum alloy temperature


## Task
In order to optimize production costs, the metallurgical plant So Hardening Steel Ltd decided to reduce electricity consumption at the stage of steel processing. I have to build a model that will predict the temperature of the steel.

## Description
* I carried out the primary analysis of the provided dataframes.
* The next step was pre-processing: clearing gaps in the data, checking for complete duplicates, changing data types.
* The target feature was defined and some features were created, which were then effectively used in training the model.
* Dataframes provided have been merged by batch number `key`
* Next, I embarked on an exploratory data analysis, during which:
* Removed most notable outliers
    * Estimated results of temperature measurements over time
    * Checked for multicollinearity
    * Estimated data distributions on the cross-correlation graph
    * It was decided to convert the data on active and reactive power according to the apparent power formula and discard some features in order to avoid retraining the model
* Before training the model, the dataframe was divided into training and test sets in a ratio of 3 to 1
* Selected target feature
* The rest of the data has been scaled
* Using auto-selection of parameters, it was determined that gradient boosting models are the most suitable for the purposes of the project
* The CatBoostRegressor model performed best with MAE = 6.5 on the test set
* Further, the analysis of the influence of features during the training of the model was carried out
* Additional cleaning of some of them from anomalies
* The model with the best parameters was again trained on the final data, which was again split and scaled
* As a result, the CatBoostRegressor model was trained with the indicator ***MAE = 5.6***, which, according to the conditions of the task, overcomes the maximum possible threshold MAE ≤ 6.0

In order to further optimize the model, it is possible to reduce the spread in temperature measurements, as the most important feature in the learning process. Perhaps a model is needed to capture the anomaly of the measurement result.

## Fields of activity

* Branch companies / Industry
* Services for business [b2b] (outsourcing consulting audit)
* IT company
* Startups

## Skills

* Pandas
* Matplotlib 
* seaborn 
* math
* machine learning
* sklearn
* xgboost
* numpy
* lightgbm
* catboost
* shap

## Tags

data science, machine learning, ML, Python, SQL, Git, Pandas, Numpy, Matplotlib, seaborn, Sklearn, Tableau, Spark, Hadoop, R, sci-py, Research, Kaggle, Algorithms, PyTorch, TensorFlow, CatBoost, xgboost, Support vector machines, gradient boosting, non-linear optimization, clustering, random forest, decision trees, regression, Reinforcement Learning, OpenCV, PIL
