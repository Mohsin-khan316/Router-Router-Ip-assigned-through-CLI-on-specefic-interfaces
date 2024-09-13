"Configure ip address" on router interface [3 mode]
#################################################

STEPS TO FOLLOW
STEPS
1 Router>enable
2 Router# Configure terminal
3 Router(config)# Hostname R1
4 R1(config)# interface f0/0
5 R1(config-if)#ip address 1.1.1.1 255.0.0.0
6 R1(config-if)# no shutdown
7 R1(config-if)# exit
---------------------------
After configuring both links are up manually and both devices are reachable to each other
