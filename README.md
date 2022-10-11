# Exercise-9
Determining IP Address, number of hosts, range of IP addresses, and broadcast IP address in a given subnet 
The subnet given is 193.16.20.35/29
The first octet has a value of 193, this means the subnet belongs to a class c

# Finding the Network Ip
since the default class is 'c', the default net mask is 255.255.255.0

# Using the AND operation to get the network Ip
The subnet 193.16.20.35/29 is equal to 10101101.00010000.00010100.00100011
The net mask of the subnet is also equal to 11111111.11111111.11111111.00000000
using the and operation, the Network Ip becomes 10101101.00010000.00010100.00000000
The Network Ip is therefore equa to 193.16.20.0

# Network address
The networ address is therefore  equal to 193.16.20.0/29

# Number of hosts 
The number of hosts for the given subnet is 254
