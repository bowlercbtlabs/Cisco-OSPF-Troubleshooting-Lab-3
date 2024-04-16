# Cisco OSPF Troubleshooting - Lab 3


### Please Note: The Frame Relay Switch is setup correctly and there is no need to troubleshoot it.


## Trouble Ticket #1

### Problem
- R1 is unable to form an OSPF neighbor relationship with R2 across the Frame Relay network.

### Desired outcome
- Configure the network so that R1 and R2 form an OSPF neighbor relationship.
- You are not allowed to use the “neighbor” command under OSPF to complete this task. 

## Trouble Ticket #2

### Problem
- After OSPF connectivity was restored between R1 and R2 you have noticed the network 2.2.2.0/24 from R2 is not showing up in R1’s Routing Table.
- Furthermore, you have also noticed the network 1.1.1.0/24 does not appear in R2’ Routing Table.

### Desired outcome
- Configure the network so that 2.2.2.0/24 appears in R1’s Routing Table and 1.1.1.0/24 appears in R2’s Routing Table.
- Once the task is completed you should be able to ping R2’s Loopback 0 interface (2.2.2.2) from R1’s Loopback 0 interface (1.1.1.1).
- Make sure that the correct subnet masks are propagated throughout the network for the loopback interfaces.
- You may not use the command “ip ospfnetwork point‐to‐point” under the interface to solve the issue.
