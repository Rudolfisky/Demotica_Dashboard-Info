# Demotica-Dashboard
In this project i am going to make a dashboard.
The dashboard will show the following:
 - Weather
 - indoor temperatures

# Front-end
[Frontend Repo](https://github.com/Rudolfisky/Demotica_Dashboard-Frontend)[![main CI](https://github.com/Rudolfisky/Demotica_Dashboard-Frontend/actions/workflows/main_CI-CD.yml/badge.svg)](https://github.com/Rudolfisky/Demotica_Dashboard-Frontend/actions/workflows/main_CI-CD.yml) 
[![CodeFactor](https://www.codefactor.io/repository/github/rudolfisky/demotica_dashboard-frontend/badge)](https://www.codefactor.io/repository/github/rudolfisky/demotica_dashboard-frontend)
[![developer CI](https://github.com/Rudolfisky/Demotica_Dashboard-Frontend/actions/workflows/development_CI.yml/badge.svg)](https://github.com/Rudolfisky/Demotica_Dashboard-Frontend/actions/workflows/development_CI.yml)<br />
<br/>
The front end will be build using the React framework.
One of the main reasons for is that i'm also using React for this semesters group project.


# Back-end
The backend will consist of both spingboot services and MQTT Esp8266 IoT devices

## Springboot services

### Temperature service
[Temperature Service Repo](https://github.com/Rudolfisky/Demotica_Dashboard-Temperature_Service)
[![main CI/CD](https://github.com/Rudolfisky/Demotica_Dashboard-Temperature_Service/actions/workflows/main_CI-CD.yml/badge.svg)](https://github.com/Rudolfisky/Demotica_Dashboard-Temperature_Service/actions/workflows/main_CI-CD.yml)
[![CodeFactor](https://www.codefactor.io/repository/github/rudolfisky/demotica_dashboard-temperature_service/badge)](https://www.codefactor.io/repository/github/rudolfisky/demotica_dashboard-temperature_service)
[![development CI](https://github.com/Rudolfisky/Demotica_Dashboard-Temperature_Service/actions/workflows/development_CI.yml/badge.svg)](https://github.com/Rudolfisky/Demotica_Dashboard-Temperature_Service/actions/workflows/development_CI.yml)<br/>
<br/>
The temerature service will be able to save data to a database and handle REST calls for certain averages such as
1. Getting average of past 10 seconds
2. Getting average of past hour
3. Getting average of past week

## MQTT Esp8266 Temperature sensor
[Esp8266 Temperature Sensor Repo](https://github.com/Rudolfisky/Demotica_Dashboard-Esp8266_Temperature_Sensor)<br />
[Esp8266 Temperature Sensor POC's Repo](https://github.com/Rudolfisky/Demotica_Dashboard-POC-Esp8266)<br />
This repo contains the hardware component that sends out data to a MQTT broker and connects to a network.
