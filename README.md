# 21_Exoplanet_machine
## Homework, Unit 21 Machine Learning

### Background
Overall, the project is to create Scikit-Learn library to create classification machine learning models to evaluate solar system data.  

From Instructions README:  Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.  To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

* Preprocess the raw data
* Tune the models
* Compare two or more models

### Getting Started
The models are located in the Instructions folder / starter_code / and then one of the 3 models.

The Support vector machine linear classifier model classified the koi fields to the koi disposition (Candidate, Confirmed, False Positive) with a Training Data Score: 84.7% and Testing Date Score of 84.6%.  After tuning the 'C': [1, 5, 10] and 'gamma': [0.0001, 0.001, 0.01], the best model grid score was 86.9% with C= 10 and gamma of 0.0001. 

The Nearest Known Neighbor (KNN) didn't appear to classify the Exoplanet dataset as accurately, with classifying the koi disposition with a 66% accuracy with a K value = 25.

The Neural Networks models did appear to get better results Normal Neural Network - Loss: 0.8594665215414593, Accuracy: 0.8691674470901489, with higher Precision, Recall, F-1, and Support metrics.

Finally attempting to use the K-MEANS model for categorizing didn't show good clustering between the ko disposition and the rest of the data.  There is likely a better way to run this model to produce better results.

### Prerequisites
The Jupyter Notebook contains all the Python libraries needed to run the models. 

### Built With

* Python [3.7.1], Jupyter [5.7.4]

