# Lab 06 - Azure RBAC

## Objective

Learn how Azure Role-Based Access Control (RBAC) is used to manage permissions.

## Tasks Completed

- Explored Access Control (IAM)
- Reviewed Role Assignments
- Examined Azure built-in roles
- Investigated permission inheritance

## Key Roles

### Reader

Can view resources but cannot make changes.

### Contributor

Can create, modify and delete resources but cannot assign permissions.

### Owner

Has full control including permission assignment.

## What I Learned

RBAC controls what users and groups can do within Azure.

Permissions should be assigned using the principle of least privilege.

Permissions can be inherited from higher scopes such as subscriptions and resource groups.

## Lessons Learned

Contributor is generally safer than Owner for day-to-day administration.

Users should normally receive permissions through groups rather than direct assignments.

## Screenshots



## Real World Scenario
If a new IT Technician joined the company I would assign the Contributor role rather than Owner.
This would allow them to manage Azure resources whilst preventing them from modifying permissions.
