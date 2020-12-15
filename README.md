# Harvard Hackathon Project: Smart Medical System
This Project was Submitted to Harvard University's Fifth Annual Hackathon. Check us out in their press, here:
https://www.seas.harvard.edu/news/2019/11/ode-code


## Check Out Some Images of the Prototype
### Home
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/1%20Home.png" />


The Problem We Address
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/2%20Problem.png" />

Smart Medical Reminders
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/3%20Smart%20Reminders.png" />

Medical Files Databasing
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/4%20Medical%20Files%20Database.png" />

Automated Health Metrics
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/5%20Health%20Metrics.png" />

Machine Learning Based Alerts
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/6%20ML%20Alerts.png" />

QR Code Scan for Emergency Data-Sourcing
<img src="https://github.com/rishabhstha/Smart-Medical-Alert/blob/master/HackHarvard_Images/7%20QR%20Code.png" />


## Our Prototype Solution
We want our solution to forecast possible emergency events, such as a heart attack, before they can happen to our user. We do this by training our neural network based machine learning model to predict whether or not the user may have a heart disease. With this model we have achieved 78% accuracy and we believe with more data points this can be improved. 

How: We inputted labelled data that contain several features (age, sex, heart rate, blood pressure and others) to a feed-forward neural network (multi-layer perceptron) and train it to classify whether or not a person with the given data has a heart disease. We previously trained and validate the data with a logistical regression approach. However, this led to an accuracy of only 76%. 

Challenges: data in which a person's heart rate is observed while having an emergency situation are quite rare. These data will be key in our future development of HealthBand so the model can better learn and differentiate an emergency situation from a non-emergency one.

Next steps: We would like to not only train the model and achieve a high accuracy but we would like to deploy the ML models to a web and mobile app where users can interact with them seamlessly.
