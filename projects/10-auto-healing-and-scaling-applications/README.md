# Auto-Healing and Scaling Applications

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

A gaming café wanted servers that could automatically recover from failures while maintaining controlled capacity limits.

## Business Requirements

- Improve application reliability
- Recover automatically from failures
- Manage capacity efficiently
- Reduce downtime

## Proposed AWS Solution

Implement Auto Scaling groups and monitoring services to support self-healing infrastructure.

## AWS Services Used

- Amazon EC2
- Auto Scaling Groups
- Launch Templates
- Amazon CloudWatch

## Architecture Diagram

<img width="1500" height="888" alt="Auto-HealingandScalingApplications" src="https://github.com/user-attachments/assets/95be0ef7-8b37-4050-bb73-83205e6b8306" />

## Architecture Summary

This solution uses Amazon EC2 Auto Scaling to automatically adjust server capacity based on workload demand while maintaining application availability.

CloudWatch monitors CPU utilization and triggers scaling actions when thresholds are reached. Launch Templates and Amazon Machine Images (AMIs) provide standardized configurations for newly created EC2 instances. Scheduled scaling events automatically increase or decrease capacity during predefined time periods.

## Key Components

| Component | Purpose |
|------------|----------|
| Auto Scaling Group | Manages EC2 capacity |
| CloudWatch Alarm | Monitors performance metrics |
| Launch Template | Defines instance configuration |
| Amazon Machine Image (AMI) | Provides standard server image |
| EC2 Instances | Host application workloads |
| Scheduled Events | Automatically adjust capacity |

## Implementation

- Configured Launch Templates
- Created Auto Scaling Groups
- Defined capacity limits
- Configured monitoring and scaling policies

## Security Considerations

- Ensured scaling resources inherited secured configurations

## Business Outcome

Created resilient infrastructure capable of recovering from failures and adapting to demand.

## Skills Demonstrated

- Cloud Operations
- Auto Scaling
- Infrastructure Monitoring
- Availability Management

## Key Learnings

- Auto Scaling concepts
- Capacity planning
- CloudWatch monitoring
- Self-healing infrastructure

## Resume Bullet

Implemented self-healing cloud infrastructure using Auto Scaling Groups, Launch Templates, and CloudWatch monitoring to improve application reliability.
