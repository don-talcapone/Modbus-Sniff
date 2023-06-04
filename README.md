# Modbus/TCP-Sniff
Modbus/TCP sniffing Lab via Factory IO and OpenPLC
I have created a Lab environment for sniff and analyze Modbus/TCP traffic in this repo.

For this:

OpenPLC Editor: Used for creating and compiling PLC program.

OpenPLC Service: Works as PLC and HMI. 

Factory IO: Contains 3D models of actuators and sensors that can interact with OpenPLC Server. 

# Lab Environment

<img src="https://github.com/don-talcapone/Modbus-Sniff/assets/135317904/01f53904-8245-4d88-a5fe-0e9c75f1ce96.png" width="60%">

It has a conveyor actuator as output and a sensor as input. In this scenario, the conveyor runs until the box reaches the sensor. The conveyor will stop when the box arrives.

<img src="https://github.com/don-talcapone/Modbus-Sniff/assets/135317904/9ba6c776-5183-4a1a-a6f2-76a0fc8f470f.png" width="60%">

Driver configured as Modbus TCP/IP server. 
# Programming

PLC is programmed so that the conveyor can be controlled with. The program has basic contactor and actuator and is created with ladder diagram. Used OpenPLC Editor for this.

<img src="https://github.com/don-talcapone/Modbus-Sniff/assets/135317904/37a90e02-8d18-4f3b-82b2-1c9f8aafa7a5.png" width="60%">

# OpenPLC configuration and service start

OpenPLC installed and configured on Ubuntu. It is important to make sure that the OpenPLC service is running correctly. 

Now we can configurate OpenPLC from web interface.

<img src="https://github.com/don-talcapone/Modbus-Sniff/assets/135317904/2c9fa4ac-63c7-40f0-a7f0-128ede766002.png" width="70%">

After the device is configured correctly, the program.st file can be uploaded from the program tab.






