# File Systems in the Cloud

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

A pet modeling agency needed a way to share files across multiple branch offices without managing physical storage infrastructure.

## Business Requirements

- Centralize file storage
- Allow access from multiple locations
- Eliminate physical storage management
- Improve scalability

## Proposed AWS Solution

Implement a managed shared file system using Amazon Elastic File System (EFS).

## AWS Services Used

- Amazon EFS
- Amazon EC2

## Architecture Diagram

<img width="1500" height="943" alt="FileSystemsintheCloud" src="https://github.com/user-attachments/assets/de258741-ad86-4c96-b0ef-68180dbe389f" />

## Architecture Summary

This solution implements Amazon EFS as a shared file system accessible by multiple Amazon EC2 instances across different Availability Zones.

Each web server mounts the same EFS file system, allowing data and application files to be shared across multiple systems while maintaining centralized storage.

## Key Components

| Component | Purpose |
|------------|----------|
| Amazon EFS | Provides shared file storage |
| Amazon EC2 | Hosts application workloads |
| EFS Mount Targets | Connect EC2 instances to EFS |
| Availability Zones | Improve resilience and accessibility |

## Implementation

- Created an Amazon EFS file system
- Configured mount targets
- Connected EC2 instances to shared storage
- Validated file access from multiple systems

## Security Considerations

- Controlled access using AWS networking and security configurations
- Implemented managed cloud storage security features

## Business Outcome

Provided scalable shared storage accessible across multiple systems without requiring on-premises file servers.

## Skills Demonstrated

- Cloud Storage
- Amazon EFS
- Infrastructure Administration
- Shared File Systems

## Key Learnings

- Difference between EBS and EFS
- Shared storage architecture
- Cloud file management

## Resume Bullet

Implemented a scalable shared file storage solution using Amazon Elastic File System (EFS) to support multi-system file access across cloud environments.

## Navigation

⬅️ [Cloud Economics](../06-cloud-economics/)

➡️ [Databases in Practice](../08-databases-in-practice/)
