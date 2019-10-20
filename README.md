# Health-Band-Alert
We want our solution to forecast possible emergency events, such as a heart attack, before they can happen to our user. We do this by training our neural network based machine learning model to predict whether or not the user may have a heart disease. With this model we have achieved 78% accuracy and we believe with more data points this can be improved. 

How: We inputted labelled data that contain several features (age, sex, heart rate, blood pressure and others) to a feed-forward neural network (multi-layer perceptron) and train it to classify whether or not a person with the given data has a heart disease. We previously trained and validate the data with a logistical regression approach. However, this led to an accuracy of only 76%. 

Challenges: data in which a person's heart rate is observed while having an emergency situation are quite rare. These data will be key in our future development of HealthBand so the model can better learn and differentiate an emergency situation from a non-emergency one.

Next steps: We would like to not only train the model and achieve a high accuracy because we would like to deploy the ML models to a web and mobile app where users can interact with them seamlessly.
