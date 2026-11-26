# Networking Concepts

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

A banking organization required a secure network architecture that controlled communication between internal resources and internet-facing systems.

## Business Requirements

- Protect internal systems
- Support public-facing applications
- Restrict unauthorized access
- Improve network security

## Proposed AWS Solution

Design a Virtual Private Cloud architecture using public and private subnets.

## AWS Services Used

- Amazon VPC
- EC2
- Security Groups
- Route Tables
- Internet Gateway

## Architecture Diagram

<img width="1350" height="747" alt="NetworkingConcepts" src="https://github.com/user-attachments/assets/ed45d8a5-afa1-48c0-863a-c6976f685969" />


## Architecture Summary

This solution uses an Amazon VPC with public and private subnets to separate internet-facing resources from internal database services. Security Groups and routing controls restrict access and protect sensitive resources.

## Key Components

| Component | Purpose |
|------------|----------|
| Amazon VPC | Provides network isolation |
| Public Subnet | Hosts web application |
| Private Subnet | Hosts database server |
| Internet Gateway | Enables internet access |
| Security Groups | Control network traffic |
| Route Table | Directs network traffic |

## Implementation

- Created a VPC
- Configured public and private subnets
- Attached internet gateway
- Created route tables
- Applied security group rules

## Security Considerations

- Protected database resources within private subnet
- Controlled traffic with security groups
- Used network segmentation

## Business Outcome

Enabled secure external access while protecting sensitive internal resources.

## Skills Demonstrated

- Cloud Networking
- Infrastructure Design
- Network Security

## Key Learnings

- Public vs Private Subnets
- Route Tables
- Internet Gateways
- Security Groups

## Resume Bullet

Designed and implemented secure AWS networking infrastructure using VPCs, subnets, route tables, and security groups.
