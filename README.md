# 21_Exoplanet_machine
Homework, Unit 21 Machine Learning

The models are located in the Instructions folder / starter_code / and then one of the 3 models.

The Support vector machine linear classifier model classified the koi fields to the koi disposition (Candidate, Confirmed, False Positive) with a Training Data Score: 84.7% and Testing Date Score of 84.6%.  After tuning the 'C': [1, 5, 10] and 'gamma': [0.0001, 0.001, 0.01], the best model grid score was 86.9% with C= 10 and gamma of 0.0001. 

The Nearest Known Neighbor (KNN) didn't appear to classify the Exoplanet dataset as accurately, with classifying the koi disposition with a 66% accuracy with a K value = 25.

The Neural Networks models did appear to get better results Normal Neural Network - Loss: 0.8594665215414593, Accuracy: 0.8691674470901489, with higher Precision, Recall, F-1, and Support metrics.

Finally attempting to use the K-MEANS model for categorizing didn't show good clustering between the ko disposition and the rest of the data.  There is likely a better way to run this model to produce better results.
