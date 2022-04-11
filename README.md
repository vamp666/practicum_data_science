# My educational Data Science projects 

This repository includes projects that I completed during my training at the Yandex.Practicum.

All of them are .ipynb files.

![Иллюстрация к проекту](https://github.com/vamp666/practicum_data_science/blob/main/rdm.jpg)

| Project Name | Description | Used Libraries |
| :------------------------------------------------------- | :---------------------: |:---------------------------|
| [Borrower reliability assessment](https://github.com/vamp666/practicum_data_science/blob/dd7e0e836f3cd2152188cb2decba8ec395417985/01%20Borrower%20reliability%20assessment/Borrower%20reliability%20assessment.ipynb) | Customer is the credit department of the bank. It is necessary to find out whether the marital status and the number of children of the client affect the fact of repaying the loan on time. | Pandas, data preprocessing |
| [Sale of apartments advertisment research](https://github.com/vamp666/practicum_data_science/blob/dd7e0e836f3cd2152188cb2decba8ec395417985/02%20Sale%20of%20apartments%20advertisment%20research/Sale%20of%20apartments%20advertisment%20research.ipynb) | I was given data from the Yandex.Realty service - an archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. I will determine the market value of properties. At this stage, my task is to set the parameters. This is necessary to build an automated model to track anomalies and fraudulent activity. | Pandas, Matplotlib, Exploratory Data Analysis, Math, matplotlib, seaborn |
| [Determining the priority tariff for the telecom company](https://github.com/vamp666/practicum_data_science/blob/dd7e0e836f3cd2152188cb2decba8ec395417985/03%20Determining%20the%20priority%20tariff%20for%20the%20telecom%20company/Determining%20the%20priority%20tariff%20for%20the%20telecom%20company.ipynb) | Based on the provided dataframes, it is necessary to describe the behavior of clients of different tariff plans, find out what tariff limits for a month will be considered sufficient, calculate the average, standard deviation and variance for these indicators. After that, it is necessary to test the hypotheses about the equality of the amounts paid by users of different tariffs, and about the equality of income from customers from Moscow and other regions. | Pandas, Matplotlib, numpy, SciPy, Statistics, Statistical Hypothesis testing, Math, functools, Seaborn |
| [Car prices determining](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/04%20Car%20prices%20determining/Car%20prices%20determining.ipynb) | Used cars sale service "Not beaten, not beautiful" is developing an application to attract new customers. In it, you can quickly find out the market value of your car. At your disposal are historical data: technical specifications, equipment and prices of cars. You need to build a model to determine the cost. | Pandas, Sklearn, Numpy, LightGBM, CatBoost, XGBoost, math |
| [Game market analysis](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/05%20Game%20market%20analysis/Game%20market%20analysis.ipynb) | I have game sales data, user and expert ratings, genres and platforms. It is necessary to identify the patterns that determine the success of the game and plan the company for 2017. Pre-processing will be carried out, sales by platform will be analyzed, the impact of reviews from critics and users on sales will be assessed, a portrait of users in each region (NA, EU, JP) will be compiled, Action and Sports genre ratings are different. | Pandas, numpy, Matplotlib, functools, statistical hypothesis testing, Seaborn, SciPy |
| [Tariff recommendation](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/06%20Tariff%20recommendation/Tariff%20recommendation.ipynb) | I have at my disposal data on the behavior of customers who have already switched to new tariffs. You need to build a model for the classification problem that will select the appropriate rate. Data preprocessing is not required - you have already done it. I have to build a model with the highest possible accuracy. For the project to be considered successful, the percentage of correct answers must be at least 0.75. |Pandas, Matplotlib, sklearn, Numpy, Python, Seaborn |
| [Customer churn prediction](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/07%20Customer%20churn%20prediction/Customer%20churn%20prediction.ipynb) | It is necessary to predict whether the client will leave the bank in the near future or not. You are provided with historical data on customer behavior and termination of agreements with the bank. Build a model with an extremely large F1-measure. To pass the project successfully, you need to bring the metric to 0.59. Check the F1-measure on the test set yourself. Additionally measure AUC-ROC, compare its value with F1-measure. | Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Math, itertools |
| [Choosing a location for an oil well](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/08%20Choosing%20a%20location%20for%20an%20oil%20well/Choosing%20a%20location%20for%20an%20oil%20well.ipynb) | Project for a mining company. We need to decide where to drill a new well. I was provided with oil samples in three regions: in each of 10,000 fields, where they measured the quality of oil and the volume of its reserves. Build a machine learning model to help determine the region where mining will bring the most profit. Possible profits and risks will be analyzed using the Bootstrap technique. | Pandas, Sklearn, Math, Numpy, Seaborn, Matplotlib, SciPy, Bootstrap, itertools, plotly |
| [Recovery of gold from ore](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/09%20Recovery%20of%20gold%20from%20ore/Recovery%20of%20gold%20from%20ore.ipynb) | I have to prepare a prototype machine learning model for "Digits". The company develops solutions for the efficient operation of industrial enterprises. The model should predict the recovery rate of gold from gold ore. Use data with mining and cleaning parameters. The model will help optimize production so as not to launch an enterprise with unprofitable characteristics. | Pandas, Sklearn, Numpy, Seaborn, Matplotlib, Math, sklearn, catboost |
| [Protection of clients personal data](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/10%20Protection%20of%20personal%20data%20of%20clients/Protection%20of%20personal%20data%20of%20clients.ipynb) | I need to protect the data of clients of the insurance company "Хоть Потоп". I will develop a data transformation method that makes it difficult to recover personal information from them. | Pandas, Matplotlib, seaborn, Numpy, Sklearn |
| [Taxi Order Prediction](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/11%20Taxi%20Order%20Prediction/Taxi%20Order%20Prediction.ipynb) | The Clear Taxi company has collected historical data on taxi orders at airports. To attract more drivers during the peak period, you need to predict the number of taxi orders for the next hour. I will build a model for such a prediction. The value of the RMSE metric on the test sample should not exceed 48. | Pandas, sklearn, numpy, LightGBM, Matplotlib, seaborn, StatsModels, sklearn |
| [Definition of toxic comments](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/12%20Definition%20of%20toxic%20comments/Definition%20of%20toxic%20comments.ipynb) | Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. That is, clients propose their edits and comment on the changes of others. The store needs a tool that will look for toxic comments and submit them for moderation. I will train the model to classify comments into positive and negative. I have a data set with markup on the toxicity of edits. It is necessary to build a model with the value of the quality metric F1 not less than 0.75. | Pandas, sklearn, NLTK, LightGBM, re, torch, transformers, catboost |
| [Customers Age Prediction](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/13%20Customers%20Age%20Prediction/Customers%20Age%20Prediction.ipynb) | I need to build a machine learning model that determines the approximate age of a person from a photo. There is a set of photos of people with an indication of their age. | Pandas, numpy, keras, Matplotlib, Seaborn, Computer Vision, Machine Learning |
| [Determining the optimum alloy temperature](https://github.com/vamp666/practicum_data_science/blob/52fcfdb0ec62db4520de1362a11bfa5bd3feb2a1/14%20Determining%20the%20optimum%20alloy%20temperature/Determining%20the%20optimum%20alloy%20temperature.ipynb) | In order to optimize production costs, the metallurgical plant So Hardening Steel Ltd decided to reduce electricity consumption at the stage of steel processing. I have to build a model that will predict the temperature of the steel. | Pandas, Matplotlib, seaborn, math, machine learning, sklearn, xgboost,  numpy, lightgbm, catboost, shap |
