# Andriod app MyCircle

# Course: Ubiquitous / Mobile Computing

Masters studies

Asha Joshi, asha.joshi@gmx.de

Dibyojyoti Sanyal, dibyojyoticemk@gmail.com 

MSc: Distributed Software Systems University: Technische Universität Darmstadt

Not availble for public use. 


# How to execute:
The project can be unzipped and imported in android studio and executed from android studio.
Please make sure the android device is GPS and Internet enabled and provides permission to the apps to use both.

Platform : Android
Pub/Sub: mosquitto MQTT (paho client iplementation)
Broker: HiveMQ MQTT broker used as default broker

Perquisites for using MyCirlce:
GPS should be enabled.
Working internet connection.

# Motivation:
Creation of a spider web of friends for helping each other in times of need by means of location tracking and exchange of messages.

# PURPOSE: 
Our project, “My Circle” is an application that was developed for assisting friends during times of need.The project focuses on how we can help our friends or they can help us irrespective of the time and location. It is an application wherein all friends are connected to each other and this connection is represented in the form of a spider web. Friends can seek help and offer help based on the trust level and also their location. 

This application was mainly developed for connecting and helping friends irrespective of their place location. Hence, for the same we have made use of Mosquitto, which is an open source message broker that implements the MQTT (Message Queuing Telemetry Transport) protocol. Communication here is happening amongst the friends and MQTT broker here takes note of the publishers and subscribers and facilitates the forwarding of messages to the subscribers. The subscribers here subscribe to a topic with the help of their respective contact numbers. Note: We used public broker provided by hivemq. 

Database Architecture: We used SQLite database and three tables called “contacts”,”msgs” and “fmsg” are used to store contacts, messages and auto forwarded messages.    

# WORKING: 

Demo URL: https://youtu.be/iQsCuiKb9Vs

Taking into consideration that all my friends in My Circle, including myself are currently at different locations in Darsmatdt and all of us are connected to each other through My Circle application, which is installed on each of our phones. Now let us assume that person A wants to buy some medicine from a medical store near Pallaswiesen Strasse, but the shop will be opened only for another 20 minutes. Person A can’t make it on time, so he/she sends a help message to friends residing near Pallaswiesen strasse. Person A gets to know about his friend’s current location with the help of the GPS which highlights the current location of friends on a map. Firstly, this will be possible only if you have a phone with an internet connection and My Circle application installed on it. Secondly, you should have added your friends in the My Circle application, in order for the application to track the latitude and longitude with exact position of your friends with the help of an algorithm. Once these conditions are satisfied then you will be able to send messages, receive messages, and seek help from your friends depending on their current location. 

# TECHNOLOGIES USED:  
Mosquitto MQTT(Mosquitto-Message Queuing Telemetry Transport), GPS - Global Positioning System,  GSM - Global System For Mobile Communication, Android Smart phone with internet connection, Google Maps 

# IMPLEMENTATION: 
We used Android Studio 2.1.2 for developing the My Circle application. And in order to facilitate the communication between the end-to-end devices, we have used the Mosquitto MQTT publish-subscribe messaging pattern. We used google maps service provided by android. For database we used SQLlite also provided in Android.    

# CONCLUSION: 
On a concluding note, we would like to inform you all that our project, “My Circle” has been successfully implemented with the help of various technologies including ubiquitous technology. This project can be an example of how mobile-to-mobile communication can be used today in the best way possible, with our present era having IoT (Internet of Things) as one of the prominent research focuses. 
