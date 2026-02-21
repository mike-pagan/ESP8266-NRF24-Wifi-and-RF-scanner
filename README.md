# ESP8266-NRF24-Wifi-and-RF-scanner

This code is made to scan available networks in your area. In the output you will see SSID, RSSI and encryption type. Also it scans channels from 0 to 125 to see if any frequency in the area is getting detected. Due to hardware limitations, you are only able to see WiFi and signal power. Hardware used is: ESP8266, NRF24L01, a 100uF Capacitor and a external PSU. 


Important!

The NRF24 module must only be connected to 3.3V. 5V will damage the module. 
