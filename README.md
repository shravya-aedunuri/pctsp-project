# pctsp-project
**Budget-Constrained Prize-Collecting Traveling Salesman Problem: a Reinforcement Learning Approach**


Greedy Algorithms for IoT Sensor Network 


This repository contains versions of two greedy algorithms for finding the optimal path for a battery powered robot in an IoT sensor network. 

*Greedy Algorithm 1* 

This version of the first greedy algorithm selects the next node based on the highest reward to  energy needed ratio that the robot can still move to. 

Usage: 
greedy_1(graph, energy_level)  

Where: 
• graph is the IoT sensor network graph. 
• energy_level is the initial energy level of the robot in Joules. 

*Greedy Algorithm 2* 

This version of the second greedy algorithm finds the next node that maximizes the ratio of reward  to energy needed. 

Usage: 
greedy_2(graph, energy_level)  

Where: 
• graph is the IoT sensor network graph. 
• energy_level is the initial energy level of the robot in Joules.

**Compilation and Execution:** This program is written in Python 3 and does not need to be  compiled. To run the program, use the following command in the terminal: 
python3 sensor_network.py  

You will be prompted to input the width x and length y of the sensor network, number of sensor nodes, transmission range in meters, number of DNs, and maximum number of data packets each DN has. 

Successful Compilation and Execution: Yes, the program can be compiled and executed successfully. 


**Testing the Program:** To test the program, simply run the script and input the desired parameters  when prompted. Here are some test cases: 

1. width = 2500m, length = 2500m, number of sensor nodes = 125, transmission range = 500m,  number of DNs = 63, maximum number of data packets = 1250 

2. width = 3500m, length = 3500m, number of sensor nodes = 175, transmission range = 700m,  number of DNs = 88, maximum number of data packets = 1750 

3. width = 4500m, length = 4500m, number of sensor nodes = 225, transmission range = 900m, number of DNs = 113, maximum number of data packets = 2250 

4. width = 5500m, length = 5500m, number of sensor nodes = 275, transmission range = 1100m, number of DNs = 138, maximum number of data packets = 2750 

5. width = 100m, length = 100m, number of sensor nodes = 10, transmission range = 20m, number of DNs = 30, maximum number of data packets = 400
