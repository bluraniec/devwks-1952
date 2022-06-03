![Intro](/readme/1.png)
# About the LAB
The goal of this lab is to showcase an example of Model-Driven Telmetry feature used in monitoring BGP neighborships. In a stable state, BGP neighbor flaps should not occur frequently. Frequent flaps indicate a problem with Circuit, Hardware, Software or Configuration. We want to monitor these flaps. You can use that information further in order to shutdown the neighbor in case of repeated alarm.  
<img align="center" width=90% src="/readme/topo.png"></img>

Upon completion of this lab you, you will be able to:
- Configure Model-Driven Telemetry on Cisco IOS-XR devices 
- Consume data streams from Network Devices using Pipeline
- Store gathered data in a database such as Influx DB
- Visualize data in real-time using Grafana tool

# Introduction
Model-Driven Telemetry (MDT) allows for near real-time measurements of operational and statistical data from networking devices. Performing advanced monitoring can trigger remedial tasks that usually require human intervention. The session will describe the architecture of an analytics platform which should give a starting point for experimenting with telemetry. Introducing MDT solution offers companies the opportunity to reduce the cost associated with large IT departments and to allocate human resources more strategically, reducing hours spent performing reactive work and focusing on more proactive activities. 
 
This lab demonstrates how streaming telemetry can be used in an environment with virtualized devices running different Operating Systems, such as Cisco IOS-XE and Cisco IOS-XR. The participants will have the opportunity to collect data from devices, analyze it and visualize in near real-time using open-source tools.

# Prerequisites
- Basics of SQL language
- Basic understanding of YANG Data Modeling
- Basic understanding of Linux

<h4 align="center">[1/6]</h4>
<h4 align="center"> <a href="/readme/1.md"> IOS-XR Model-Driven Telemetry :arrow_right: </a> </h4>
