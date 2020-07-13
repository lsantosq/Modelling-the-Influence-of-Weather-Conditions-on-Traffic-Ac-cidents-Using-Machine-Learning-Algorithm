# Modelling the Influence of Weather Conditions on Traffic Accidents Using Machine Learning Algorithms

Weather conditions, among several other factors, can affect the rate of road traffic collisions leading to significant financial and personal losses. The aim of this project is to model the impact of weather conditions on road safety using three machine-learning algorithms.

The following machine laerning models are used:
* **Supervised learning**: Linear regression, random forest and KNN.
* **Unsupervised learning**: DBSCAN, Mean shift, K-Means

This study is only be for the city of Calgary. [Traffic accidents data](https://data.calgary.ca/Transportation-Transit/Traffic-Incidents/35ra-9556) is obtained from the city’s website and weather data will be obtained from [Government of Canada’s website](https://weather.gc.ca/). These datasets are publicly available for non-commercial use.

Classes were created to use Random forest and KNN as classifiers and linear regression is used as usual. For metrics, accuracy was selected for classification and squared error for regression.

The [final report](final_article.pdf) can be found in this repository. At the end of the day, a model was developed using temperature, snowfall and rainfall to predict the total number of accidents for the city of Calgary and can be used by emergency services to proactively plan resources allocations.
