# Single-LAN

A single LAN segment was designed using the 192.168.0.0/24 private IP subnet. Host IP addressing was allocated to all end devices, and the edge router was configured and brought online to enable internal connectivity and routing services

# CLI - COMMANDS
ROUTER # enable

ROUTER # config terminal

ROUTER (config) # int gig 0/0/0

ROUTER (config - if) # ip address 192.168.0.1 255.255.255.0

ROUTER (config) # no shutdown
