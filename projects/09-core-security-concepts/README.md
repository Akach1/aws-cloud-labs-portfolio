# Core Security Concepts

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

A stock exchange wanted to ensure support engineers only had access required for their job responsibilities.

## Business Requirements

- Enforce least privilege
- Improve security controls
- Restrict unnecessary access
- Enhance account management

## Proposed AWS Solution

Implement Identity and Access Management (IAM) policies, groups, and roles.

## AWS Services Used

- AWS IAM
- Amazon EC2
- Amazon RDS

## Architecture Diagram

<img width="1500" height="835" alt="CoreSecurityConcepts" src="https://github.com/user-attachments/assets/9ca22686-8e4e-4caf-ab84-cf82e189c2f2" />

## Architecture Summary

This solution implements AWS Identity and Access Management (IAM) using groups and managed policies to enforce least-privilege access.

Support engineers are assigned to an IAM group with read-only permissions for Amazon EC2 and Amazon RDS resources. IAM policies allow users to view infrastructure resources while preventing administrative actions that could impact system availability.

## Key Components

| Component | Purpose |
|------------|----------|
| IAM User Group | Groups users with similar responsibilities |
| IAM Policies | Define allowed actions |
| Support Engineers | Access cloud resources |
| Amazon EC2 | Compute resources |
| Amazon RDS | Database resources |
| Read-Only Permissions | Restrict administrative actions |

## Implementation

- Created IAM users
- Created IAM groups
- Attached managed policies
- Applied least-privilege access controls

## Security Considerations

- Enforced role-based access
- Minimized excessive permissions
- Improved identity security

## Business Outcome

Reduced security risk by ensuring users only had access necessary for their responsibilities.

## Skills Demonstrated

- Identity Management
- Cloud Security
- IAM Administration
- Access Control

## Key Learnings

- Principle of least privilege
- IAM user management
- Group-based access control
- Security governance

## Resume Bullet

Implemented AWS IAM security controls using users, groups, and managed policies while applying least-privilege access principles.
