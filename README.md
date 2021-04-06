# Exoplanet-Exploration

![alt text](https://github.com/Claude-Hanfou/Exoplanet-Exploration/blob/main/Images/exoplanets.jpg "planet")


### Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data, this project uses different machine learning models  (SVM, Logistic Regression, Sequential, Random Forest, KNN) capable of classifying candidate exoplanets from the raw dataset.

### Processing the Data

* Preprocessed the dataset prior to fitting the model.
* Performed feature selection and remove unnecessary features.
* Used MinMaxScaler to scale the numerical data.
* Separated the data into training and testing data.


### Tuning Model Parameters

* Used GridSearch to tune model parameters.
* Tuned and compared five(05) different classifiers.


### Findings
I predicted that the Deep Learning model would have the highest accuracy because it used more than one layer of hidden nodes. The SVM and Logistic Regression models had around the same accuracy (0.87) once they were hypertuned with the GridSearch parameters. The Deep Learning model had a slightly higher accuracy, (0.89). The scores of the hypertuned GridSearch models slightly increased when compared to the test scores of the regular SVM and Logistic Regression models. Overall, the Deep Learning model seemed to be the most accurate.
