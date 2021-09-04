# Indoor Positioning System (Wi-Fi)
Fingerprinting-Based indoor positioning system built using:

PCAP + POCO net libraries - c++ part :
  to receive the wifi packets, processing them and sending the result to the flask server
  
Flask + sqlalchemy - python part: 
  to receive the http requests from the c++ program and store the received data in an SQL database

