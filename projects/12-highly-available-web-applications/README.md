# Highly Available Web Applications

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

A travel agency needed its web application to remain available even if individual infrastructure components failed.

## Business Requirements

- Eliminate single points of failure
- Improve availability
- Support traffic growth
- Increase resilience

## Proposed AWS Solution

Design a highly available multi-tier architecture using load balancing, auto scaling, managed databases, and content delivery services.

## AWS Services Used

- Amazon EC2
- Elastic Load Balancer
- Auto Scaling Groups
- Amazon RDS
- Amazon CloudFront
- Amazon Route 53
- Amazon S3
- Amazon CloudWatch

## Architecture Diagram

<img width="1500" height="853" alt="HighlyAvailableWebApplications" src="https://github.com/user-attachments/assets/7642170d-e5e1-4b62-b35e-33936f1a79da" />

## Architecture Summary

This solution implements a highly available web application architecture using Route 53, CloudFront, Elastic Load Balancing, Auto Scaling, EC2, and Amazon RDS. Traffic is distributed across multiple Availability Zones to improve resiliency and fault tolerance.

## Key Components

| Component | Purpose |
|------------|----------|
| Route 53 | DNS resolution |
| CloudFront | Content delivery and caching |
| Elastic Load Balancer | Distributes application traffic |
| Auto Scaling Group | Manages EC2 capacity |
| EC2 Instances | Host web application |
| Amazon RDS | Database services |
| CloudWatch | Monitoring and scaling |

## Implementation

- Configured load balancing
- Implemented Auto Scaling
- Enabled Multi-AZ database deployment
- Configured DNS routing
- Integrated content delivery services

## Security Considerations

- Improved resilience through distributed architecture
- Reduced service disruption risks

## Business Outcome

Provided a highly available cloud architecture capable of maintaining service during infrastructure failures.

## Skills Demonstrated

- Cloud Architecture
- High Availability Design
- Scalability
- Load Balancing
- Operations Monitoring

## Key Learnings

- Multi-tier architectures
- Fault tolerance
- Elastic scaling
- High availability strategies

## Resume Bullet

Designed and implemented a highly available AWS architecture using load balancing, Auto Scaling, Route 53, CloudFront, and Multi-AZ database deployments to improve resilience and service continuity.
## Navigation

⬅️ [Connecting VPCs](../11-connecting-vpcs/)

➡️ Portfolio Complete 🎉
