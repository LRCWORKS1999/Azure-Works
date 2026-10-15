# Lab 10 - Hybrid Identity

## Objective

Understand how on-premises Active Directory integrates with Microsoft Entra ID to provide a hybrid identity environment.

## Tasks Completed

- Reviewed Microsoft Entra ID user properties
- Confirmed on-premises directory synchronization
- Verified Password Hash Synchronization
- Reviewed synchronized user attributes
- Examined hybrid identity configuration

## Environment

On-Premises Domain:
crystal.local

Synchronization Tool:
Microsoft Entra Connect

Authentication Method:
Password Hash Synchronization (PHS)

## What I Learned

Hybrid Identity allows organisations to maintain a single identity across both on-premises and cloud services.

Microsoft Entra Connect synchronises users, groups and directory attributes from Active Directory to Microsoft Entra ID.

This allows users to access:

- Microsoft 365
- Teams
- SharePoint
- Intune
- Azure

using a single identity.

## Real World Experience

I implemented Microsoft Entra Connect within our production environment.

Tasks included:

- Configuring directory synchronization
- Enabling Password Hash Synchronization
- Verifying successful synchronization
- Enrolling company PCs into Microsoft Intune
- Enrolling company tablets into Microsoft Intune
- Supporting hybrid identity management

The Entra Connect server is currently hosted on the none DC server and synchronises user identities from the on-premises Active Directory environment to Microsoft 365 services.

## Screenshots

### Hybrid User Properties

<img width="1553" height="899" alt="image" src="https://github.com/user-attachments/assets/77062db6-b266-4c13-85ac-917a4e4cbf37" />


### On-Premises Synchronization Details

<img width="994" height="486" alt="image" src="https://github.com/user-attachments/assets/70f77433-33ca-4b51-b7c6-a194018fe4f2" />


## Lessons Learned

Hybrid identity provides a bridge between traditional Active Directory environments and cloud services.

Users can be managed centrally while maintaining access to both on-premises and cloud resources.

Password Hash Synchronization simplifies authentication and reduces infrastructure requirements compared to federation solutions.
