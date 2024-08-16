# Weather-Prediction
Weather Forecasting using LoRa and Machine Learning
Introduction
Weather forecasting using LoRa is a simplified and cost effective method for predicting weather. We will be using it to predict real time weather condition at high altitudes.

Problem Statement
Done using Satellite Communication

Expensive
Limited Coverage
Power Limitation
Latency
Signal Degradation
Cellular Communication (3G, 4G) not possible

Objectives
To develop LoRa communication system for real time weather data transmission.
To design and implement prototype system for real time weather forecasting.
To investigate the use of machine learning algorithms for weather prediction.
Literature Review
Machine Learning can perform better than the traditional mathematical models in the scope of weather prediction over time through research into related work coupled with our experimentation.[5]
Recently, there has been growing interest in the possibility of using neural networks for both weather forecasting and the generation of climate datasets.[10]
LoRa can be considered as a good candidate in solving the complexity of the problems in the development of IoT in the next future.[2]
The experiment with LoRa transmission has shown that the LoRa technology is very suitable for the air pollution system especially in long range transmission compared to other wireless transmission techniques.[11]
Methodology
Weather data from BMP 180 and DHT 11 sensor are transmitted from transmitter to receiver section using LoRa. Arduino at receiver station sends the sensor data to the Node Server. Node server displays the live weather data using chart.js. Node servers calls API to Flask server for weather prediction. Flask server calls machine learning model when user enters input parameters for weather prediction.
