# Single-LAN
# DEFINITION

A Single LAN (Local Area Network) is a network in which all devices are connected within a limited geographic area, such as an office, building, or floor, allowing them to communicate, share resources (like files and printers), and access a common gateway or router. All devices in a single LAN typically share the same IP subnet and network segment.

# PROJECT DEFINITION
A single LAN segment was designed using the 192.168.0.0/24 private IP subnet. Host IP addressing was allocated to all end devices, and the edge router was configured and brought online to enable internal connectivity and routing services

# CLI - COMMANDS
ROUTER # enable

ROUTER # config terminal

ROUTER (config) # int gig 0/0/0

ROUTER (config - if) # ip address 192.168.0.1 255.255.255.0

ROUTER (config) # no shutdown
