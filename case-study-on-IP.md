# Cisco Packet Tracer Networking Labs

## Overview

This repository contains basic networking experiments created using Cisco Packet Tracer. These labs demonstrate IP addressing, network connectivity, and common networking scenarios for beginners.

## Experiments

### 1. Point-to-Point Connection

**Objective**
- Connect two PCs through a switch.
- Assign IP addresses in the same network.
- Verify connectivity using the `ping` command.

**Result**
- Communication was successful because both PCs were configured in the same network.

### 2. One PC with IP Address and One PC Without IP

**Objective**
- Understand the importance of IP addressing.
- Observe what happens when one device has no IP configuration.

**Configuration**
- PC0: 192.168.1.10
- PC1: No IP Address

**Result**
- Ping failed because the destination PC was not assigned an IP address.

### 3. Two PCs with Different IP Classes

**Objective**
- Understand communication between different networks.

**Configuration**
- PC0: 10.0.0.1/8 (Class A)
- PC1: 192.168.1.2/24 (Class C)

**Result**
- Ping failed because the PCs were on different networks and no router was configured to route traffic.

## Learning Outcomes

After completing these experiments, you can understand:

- Basic network topology
- IP address configuration
- Network communication using Ping
- Difference between same-network and different-network communication
- Why IP configuration is required for successful communication
