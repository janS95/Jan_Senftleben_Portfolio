# Jan Senftleben Project Portfolio


# [Project: Analyzing a distribution network](https://github.com/janS95/analyzing_a_distribution_network)

* Read network data from a distribution network in the USA
* Node attributes: Population, Location (Latitude, Longitude)
* Edge weight: Travelling Cost for this connection
* Plot the graph diagram corresponding to location
* Highlight NYC and LA for better orientation
* Use population (Node Size) and travelling cost (Edges width) for styling
* Red Edges: travelling cost greater than 770 $

![alt text](images/network.png "Distribution Network")


# [Project: Analyzing weather data](https://github.com/janS95/analyzing_weather_data)
## Was 2015 a record breaking year temperature-wise?

* Weather data from Ann Arbor, Michigan from the years 2005 - 2015
* Split data in period 2005 - 2014 and 2015
* Created diagram with maximum and minimum temperatures from 2005 - 2014 by day of the year
* Mark record breaking lows & highs in 2015

![alt_text](images/weather_resized.png "Weather")


# [Project: Predictions on E-Mail network](https://github.com/janS95/predictions_on_email_network)

* Read E-Mail network dataset
* Node attributes: Department, Management Salary
* Generated features for predicting if employee has management salary
* Used Random Forest Classifier
* AUC-Score: 0.948
* Generated features for predicting future connections between employees
* AUC-Score: 0.901
* TODO: Optimize features, optimize classifier, try other classifiers, gridsearch
