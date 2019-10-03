# AWS_iot_IIIT

we are using linkit one as micro-controller.

# Key features of linkit
1. All-in-One connectivity: Based on MediaTek MT2502A SoC, offering comprehensive communications and media options, with support for GSM, GPRS, Bluetooth 2.1 and 4.0, SD Cards, and MP3/AAC Audio, as well as Wi-Fi and GNSS (hardware dependent)

2. LinkIt ONE development board from partner Seeed Studio with similar pin-out to the Arduino UNO enabling a wide range of peripheral and circuits to be connected to the board

3. LinkIt ONE SDK (for Arduino) offering instant familiarity to Arduino developers and a easy to learn toolset for beginners

4. This code publishes message to topic='dhairya' on aws iot core
you have to store data recevied to dyanamodb or any other database

# JSON_to_TOPIC
This code sends data to aws iot topic="dhairya" in json format, and now we are able to get that data on dynamodb.
we now have to retrive data from data base and show on a website

# Work to-do
1. we have to take real data from real sensors like gps, temperature ,gas etc and send them to aws database
2. In aws we have to set period of data accteptance to be set from custom website
3. we have to bulit this custom website 
4. we will use node js and dyanamo db for website.
