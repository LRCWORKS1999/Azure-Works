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

<img width="1883" height="826" alt="Role Assignments" src="https://github.com/user-attachments/assets/43055681-535b-469d-a99d-2c4136da1fa9" />
<img width="1808" height="786" alt="Role Assignment" src="https://github.com/user-attachments/assets/86b6ff0a-ce35-4200-9bf0-ac0d0d437a4e" />
<img width="1823" height="829" alt="Resourse Group IAM" src="https://github.com/user-attachments/assets/7c19674a-a41d-4174-a4f0-68962ff6ce32" />




## Real World Scenario
If a new IT Technician joined the company I would assign the Contributor role rather than Owner.
This would allow them to manage Azure resources whilst preventing them from modifying permissions.
