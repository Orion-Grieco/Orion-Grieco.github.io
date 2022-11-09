---
title: DHT-22 Temperature and Humidity Sensor
emoji: 🌡️
metaDescription: DHT-22 Sensor Project
date: 2019-01-01T00:00:00.000Z
summary: A project created to record and display live data from a collection of DHT22 temperature and humidity sensors.
tags:
  - C++
  - Python
  - Jupyter Notebook
---
Link to Repo : https://github.com/Orion-Grieco/dht_22
### Task

The task was brought about via a high-school project that stemmed from basic machine-learning. The task itself involved making a network of DHT-22 humidity and temperature sensors connected to Arduino UNO boards with XBee receivers mounted to them. The intent of the sensors was to actively record and compile data, and the XBee sensors would be used to and transmit data to an XBee sensor designated as a receiver whereas the others would transmit recorded data.

### Solution

The end result of this was creating a net-work of DHT-22 sensors with XBee receivers mounted to Arduino UNO boards in order to record, compile, and transmit data. A program called XCTU was used to organize and set up the network of XBee receivers, and the data was ultimately compiled into a CSV file through a Python program that would format the data received from the XBee receivers. The data in the CSV file would then be read into a Jupyter Notebook to be displayed on a Jupyter Notebook page.