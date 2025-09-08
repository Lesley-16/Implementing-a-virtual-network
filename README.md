# Implementing-a-virtual-network

## Project Overview
This project demonstrates the implementation of a Virtual Network (VNet) in Microsoft Azure. The goal is to establish a secure and scalable network infrastructure that supports communication between Azure resources.

## Objectives
- Create a Virtual Network with custom address space
- Define subnets for resource segmentation
- Implement Network Security Groups (NSGs) for traffic control
- Establish VNet peering for cross-network communication

## Architecture
The architecture includes:
- A primary Virtual Network (VNet)
- Multiple subnets for different resource types (e.g., ubuntuFinanceVM, ubuntuSEOVM)
- NSGs associated with subnets to control inbound/outbound traffic
- VNet peering to enable communication between VNets

## Steps Taken
1. **Created a Virtual Network** with a defined address space (e.g., 10.0.0.0/16)
2. **Defined subnets** within the VNet (e.g., 10.0.1.0/24 ubuntuFinanceVM, 10.0.2.0/24 for ubuntuSEOVM)
3. **Created and associated NSGs** to control traffic to/from subnets
4. **Configured VNet peering** to allow communication between different VNets
5. **Created 2 ubuntu Virtual Machines**
6. **Connect to virtual machines using Bastion** by using username and password i have used when creating virtual machine.
7. **Start communication bettween virtual machines** using bash prompt.

## Technologies Used
- Microsoft Azure
- Azure Virtual Network
- Azure Network Security Groups
- Azure Portal

## Future Improvements
- Implement Azure Firewall for centralized traffic control
- Integrate with Azure Monitor for network diagnostics
- Automate deployment using ARM templates or Terraform
