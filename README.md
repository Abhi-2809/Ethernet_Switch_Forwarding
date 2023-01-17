# Ethernet_Switch_Forwarding

This repository contains code for Implementing an ethernet switch forwarding engine using Python. We wrote a script to learn the MAC addresses along with the input port number as the user enters the input values. When the ethernet switch encounters a destination MAC address that it hasn't learnt yet, then it will forward the information to all the ports except the input port. When it receives a destination MAC address that it has already learnt then it will forward the information to that specific port.

To generate the MAC Adresses, run the following code
```
python generate_adress.py
```

To run the code for ethernet switch forwarding just run the following command
```
 python ethernet_forwarding.py
```
