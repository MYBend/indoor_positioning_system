# Indoor Positioning System (Wi-Fi)
Fingerprinting-Based indoor positioning system built using:

PCAP + POCO net libraries - c++ :
  to receive the packets treting them and sending the result to the flask server
  
Flask + sqlalchemy - python : 
  to receive the http requests from the c++ program and store the received data in an SQL database

