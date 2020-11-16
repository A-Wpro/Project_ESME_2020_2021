# Projet SD-WAN-ReinforcementLearning
xOptimization of resource allocation in software-defined wide area network SD-WAN
Supervision: Wail Benfatma + Abdulhalim Dandoush
## Abstract:
Virtualization and Software-Defined Networking (SDN) technologies are gradually gaining ground not only in data centers but also in WAN and RAN due to several key features mainly flexibility in scaling in and out the allocated resources and simplicity of configuration and troubleshooting. SDN applied to WAN enables management in a centralized manner and thus provides the ability to enhance application performance thanks to the global on-time knowledge of the network resources utilization and the demande requirement. 
## Environment:
This work is related to the thesis of Ons Fares (a PHD Student at UPEC supervised by A. Dandoush & Nadjib AitSaddi). We have implemented as a first step a SD-WAN architecture based on Open Network Operating System ONOS SDN controller and other open-source tools for supporting handling and dealing with requirements of a new generation of applications such as: bandwidth, loss and latency. Thousands of such applications should run across multiple geographical distributed data centers interconnected via WANs. It can be seen that handling such a huge traffic within a WAN needs powerful path computation and optimization techniques able to enhance the quality of service. We formulate as a second step the path computation problem as an Integer Linear Program. 
## Objectives:
We aim at the evaluation of some possible solutions (e.g., different objective functions) via a real emulated SD-WAN and simulated traffic profiles. In order to assess the performance of any proposed solution, we will compare results to the shortest path algorithm and some other work in the letterature. We want to assess the profit of Reinforcement learning techniques for handling the traffic on real time where the model can learn the quasi-optimal path for a given flow traffic. We should model the system as a Decision Markov Chain with some known states and actions to go from a state to another with some predefined award. Comparing the result of operational research and RL is an important goal of this project.
## Bonus:
We may think about features to be stored to construct our own dataset for ML/DL application targets as we will have real SD_WAN running system of configurable topology (e.g., number of switches, links and hosts can vary through parameters) in the datacenter of the school. 
Keywords : Wide-Area Networks,  Software Defined Networking, Optimisation, Integer Linear Program, ONOS, RL, Q-Learning.
