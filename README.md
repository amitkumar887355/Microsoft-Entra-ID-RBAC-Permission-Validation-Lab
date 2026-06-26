# Microsoft-Entra-ID-RBAC-Permission-Validation-Lab

# Objective
To understand and compare permissions between User Administrator and Global Administrator roles in Microsoft Entra ID.

# Environment
Microsoft Azure
Microsoft Entra ID
Test Tenant
# Lab Tasks Performed
1. User Creation
Created two test users.
Verified default user permissions.
2. Role Assignment
Assigned User Administrator role to test user "Tom".
Compared permissions with Global Administrator.
3. Permission Testing

User Administrator

Create Users ✅
Bulk Create Users ✅
Enable MFA ✅
Manage User Accounts ✅
View Sign-in Logs ❌
View Audit Logs ❌
Add Custom Domain ❌

Global Administrator

Create Users ✅
Bulk Create Users ✅
Enable MFA ✅
View Sign-in Logs ✅
View Audit Logs ✅
Invite External Users ✅
Add Custom Domain ✅
Full Tenant Management ✅

# Key Learning
This project demonstrates how Microsoft Entra ID uses Role-Based Access Control (RBAC) to enforce least-privilege access and secure identity management.

# Skills Demonstrated
Microsoft Entra ID
RBAC
Identity and Access Management (IAM)
MFA Configuration
Azure Administration
User Lifecycle Management**
