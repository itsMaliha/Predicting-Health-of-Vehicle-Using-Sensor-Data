# Predicitve Healh Maintenance for Vehicles by Analyzing Sensor Data
This project aims to predict the health of the vehicle by analyzing vehicle sensor data and sends the result to the user via email.

The complexity of vehicles is forever increasing with advancement of technology This increases the probability of accidents caused by vehicle related critical reasons. Keeping that in mind, we propose a Predictive Health Maintenance (PHM) system that analyzes the vehicle by obtaining sensor data. The LSTM approach for binary classification is used for processing the obtained data in the Raspberry Pi. The Raspberry Pi is used to create a plug and play module connected to the vehicles OBD-II port to perform processing of real time data. Eventually, the system notifies the relevant party of their vehicles health by sending a notification on their smart phone. 

In order to categorize the data as Training or Testing it is imperative to first obtain large amount of vehicle sensor data. Unfortunately, this data could not be obtained partially due to the lack of response from numerous vehicle service centers but mostly due to the pandemic. However, a similar data set of the NASA Turbofan Jet Engine (NASA, n.d.) was available and so, we laid the foundation of our system using this data set.

The model is accurate up to 98.6% based on the given test data.
