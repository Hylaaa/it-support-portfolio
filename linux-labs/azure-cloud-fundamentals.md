# Azure Cloud Fundamentals Lab

This lab documents my hands-on learning with Microsoft Azure cloud basics.

## Topics Covered
- What is cloud computing
- Azure regions and resources
- Virtual machines
- Resource groups

## Azure Account
- Azure Free Tier
- Portal: https://portal.azure.com

## Lab Activities

### Create a Resource Group
- Created a resource group to organize cloud resources
- Selected nearest region for deployment

### Create a Virtual Machine
- OS: Ubuntu Linux
- Size: B1s (free-tier eligible)
- Authentication: SSH key / password
- Purpose: Practice basic cloud VM management

### Connect to VM
```bash
ssh username@vm-ip-address
```

## Basic VM Management
- Start VM
- Stop VM
- Delete VM to avoid charges

## What I Learned
- Difference between on-premise and cloud computing
- How Azure organizes resources
- Importance of stopping unused resources to control cost
- Basic cloud security awareness
