# Databases in Practice

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

An insurance company wanted to reduce operational overhead, improve database availability, and increase efficiency.

## Business Requirements

- Reduce manual database management
- Improve availability
- Improve scalability
- Enhance operational efficiency

## Proposed AWS Solution

Implement Amazon RDS with high availability features and managed database services.

## AWS Services Used

- Amazon RDS
- Read Replicas
- Multi-AZ Deployments

## Architecture Diagram

<img width="1500" height="830" alt="DatabasesinPractice" src="https://github.com/user-attachments/assets/e20a133e-314e-48a6-a588-6b3084b48bc5" />

## Architecture Summary

This solution uses Amazon RDS with Multi-AZ deployment and read replicas to improve database availability, performance, and disaster recovery capabilities.

Customer applications send write requests to the primary database instance while read traffic can be distributed to replicas. Multi-AZ replication provides automatic failover if the primary instance becomes unavailable.

## Key Components

| Component | Purpose |
|------------|----------|
| Amazon RDS Primary Instance | Handles database operations |
| Read Replica | Improves read performance |
| Standby Replica | Supports failover and resilience |
| Customer Application | Generates database traffic |

## Implementation

- Configured Amazon RDS
- Implemented Multi-AZ architecture
- Explored Read Replica functionality
- Evaluated failover capabilities

## Security Considerations

- Utilized managed database security controls
- Implemented database access restrictions

## Business Outcome

Reduced database administration workload while improving reliability and performance.

## Skills Demonstrated

- Database Administration
- High Availability
- Cloud Databases
- Amazon RDS

## Key Learnings

- Managed databases
- Multi-AZ resilience
- Read replication
- Database scalability

## Resume Bullet

Configured managed database infrastructure using Amazon RDS with Multi-AZ deployments and read replicas to improve availability and operational efficiency.
