# AirlinePassengerSatisfaction
INTRODUCTION

This data is given by an airline organization. Original name of the company is not given so we call it as Invistico_Airline.


The main objective of the analysis is to predict whether a potential customer will be satisfied with the service offered and to identify which factors expressed by customers most influence satisfaction.

The selected dataset contains a total of 23 variables and 129,880 observations. The variables are:

1. satisfaction: The overall satisfaction level of the customer. It is a categorical variable with options "satisfied" or "dissatisfied".
2. Gender: The gender of the customer. It is a categorical variable with options "male" or "female".
3. Customer Type: Whether the customer is a "loyal customer" or a "disloyal customer".
4. Age: The age of the customer.
5. Type of Travel: This column indicates the purpose of the customer's travel. It is a catagorical variable with two possible values: "Personal Travel" or "Business travel".
6. Class: The class of travel, such as "Eco","Eco Plus" or "Business"
7. Flight Distance: The distance of the flight.
8. Seat comfort: Customer rating of seat comfort.
9. Departure/Arrival time convenient: Customer rating of convenience of departure/arrival times.
10. Food and drink: Customer rating of food and drink quality.
11. Gate location: Customer rating of gate location.
12. Inflight wifi service: Customer rating of inflight Wi-Fi service.
13. Inflight entertainment: Customer rating of inflight entertainment options.
14. Online support: Customer rating of online customer support.
15. Ease of Online booking: Customer rating of ease of online booking.
16. On-board service: Customer rating of on-board service provided by the airline.
17. Leg room service: Customer rating of leg room service provided during the flight.
18. Baggage handling: Customer rating of baggage handling.
19. Checkin service: Customer rating of check-in service.
20. Cleanliness: Customer rating of cabin cleanliness.
21. Online boarding: Customer rating of online boarding process.
22. Departure Delay in Minutes: The departure delay in minutes for each flight.
23. Arrival Delay in Minutes: The arrival delay in minutes for each flight

 MODEL TRAINING
 
Classification Algorithms

1. Naive Bayes
2. Decision Tree
3. Random Forest
4. Ada Boost
5. XG Boost
6. Logistic Regression

Perfomance evaluation

Confusion Matrix: It is a matrix of size 2×2 for binary classification with actual values on one axis and predicted on another.

Accuracy Score: Accuracy is the measure of correct predictions made by our model.It is equal to the number of correct predictions made upon total number of predictions made by the model.

Precision Score: It is defined as the ratio of true positives to the sum of true andfalse positives. It is also known as Positive Predictive Value (PPV).

Recall Score: It is defined as the ratio of true positives to the sum of true positives and false negatives. It is also called True Positive Rate (TPR) or sensitivity.

F1 score: It is the weighted harmonic mean of precision and recall. The closer the value of the F1 score is to 1.0 , the better the expected performance of the model is.

OBSERVATION

Here there is difference between the accuracy of balanced data and imbalanced data.

so we can choose the balanced data with XGBoost has best model

CONCLUSION


Here we first fit the model using imbalanced data with the accuracy and f1 score corresponding that model. Next we get a better model when we use balanced data . So here balanced data gives better accuracy and f1 score.

In conclusion, this notebook provides valuable insights into customer satisfaction in the airline industry. Factors such as inflight entertainment, seat comfort, ease of online booking, and online support have a significant impact on satisfaction levels.

The factors on which airlines needs to focus more is on the 'Arrival Delay in Minutes' and 'Departure Delay in Minutes'

Based on the analysis, we recommend focusing on improving these areas to enhance customer experiences and increase satisfaction.

The factors on which airlines needs to focus more is on the 'Arrival Delay in Minutes' and 'Departure Delay in Minutes'
