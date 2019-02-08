# bachelor-thesis
Thesis for bachelor degree of Software Engineering, Tsinghua University.

## Introduction

Thesis: Design and Implementation of Campus Bike Sharing System Based on LoRaWAN

Several other repos under this account:

* `loraarchlab/device-app`: Application installed in mobile LoRaWAN device. It sends GPS info LoRaWAN gateway.

* `loraarchlab/lora_gateway`: Serve as reference implementation for LoRaWAN gateway. It receives the LoRa singal from LoRaWAN device and relays it to network server via IP connection.

* `loraarchlab/loraserver-setup`: Ansible script for network server deployment. Using HTTP post to send GPS data to the centrolized monitor.

* `loraarchlab/server-app`: Centrolized monitor rendering the locations of LoRaWAN device on map in real time. 
