# blynk-alexa-lambda
Lambda Code for hitting Blynk API

Included in this repo is code for a lambda function that hits the blynk HTTP "api" if you want to call it that. And the code for an Alexa skill that will hit the lambda function to interact with the Blynk "api".

You have to create the lambda function first and then create an Alexa skill that will use that lambda function. 

This is all of course after you code the ESP8266 with the code required for the Blynk application and also you need to setup the Blynk app on your phone and create a project there on it to get an auth token and test that it works with your device. 
