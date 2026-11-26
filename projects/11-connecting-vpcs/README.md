# Connecting VPCs

## Related Certificate

This project was completed as part of the AWS SimuLearn Cloud Practitioner learning path.

Certificate available in this directory.

## Business Scenario

The marketing department required separate network environments while maintaining communication between departments.

## Business Requirements

- Maintain network isolation
- Enable secure connectivity
- Preserve departmental separation
- Improve communication

## Proposed AWS Solution

Implement AWS VPC Peering connections between isolated virtual networks.

## AWS Services Used

- Amazon VPC
- VPC Peering
- Route Tables
## Architecture Diagram

<img width="1500" height="830" alt="ConnectingVPCs" src="https://github.com/user-attachments/assets/59ba2620-2442-49bf-9b9f-65db0404474f" />

## Architecture Summary

This solution connects separate departmental VPCs through VPC Peering, enabling secure communication while maintaining network isolation.

Route tables and peering connections allow resources within the Marketing, Finance, and Developer environments to communicate without exposing traffic to the public internet.

## Key Components

| Component | Purpose |
|------------|----------|
| Marketing VPC | Hosts departmental resources |
| Finance VPC | Hosts financial services |
| Developer VPC | Hosts development resources |
| VPC Peering Connections | Enable communication |
| Route Tables | Direct network traffic |

## Implementation

- Configured multiple VPCs
- Created VPC Peering connections
- Updated route tables
- Tested network connectivity

## Security Considerations

- Maintained separation between environments
- Controlled communication through routing policies

## Business Outcome

Enabled communication between departments while preserving isolated network environments.

## Skills Demonstrated

- AWS Networking
- VPC Architecture
- Routing
- Cloud Infrastructure

## Key Learnings

- VPC isolation
- VPC Peering
- Network communication
- Route management

## Resume Bullet

Configured AWS VPC Peering and routing policies to enable secure communication between isolated cloud network environments.
