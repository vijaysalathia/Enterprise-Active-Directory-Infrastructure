# Project 1 — Enterprise Active Directory Infrastructure

## Description
Built a simulated enterprise domain environment using Windows Server and Active Directory Domain Services. Implemented department-based organizational units, user management, security groups, and controlled access to shared resources using NTFS and share permissions.

---

## Company Scenario
**ABC Technologies**

The company has multiple departments and wants centralized identity management, controlled resource access, and structured user administration using Active Directory.

---

## Departments
- HR
- IT
- Finance
- Sales

Each department has its own users and restricted access to resources.

---

## Organizational Unit Structure

```
ABC_Technologies
│
├── Users
│   ├── HR
│   ├── IT
│   ├── Finance
│   └── Sales
│
├── Groups
│
└── Computers
```

---

## Security Groups Created

| Group Name | Purpose |
|-----------|--------|
| HR_Group | Access to HR resources |
| IT_Group | Access to IT resources |
| Finance_Group | Access to Finance resources |
| Sales_Group | Access to Sales resources |

---

## File Server Structure

```
C:\ABC_Technologies
│
├── HR_Projects
├── IT_Projects
├── Finance_Projects
└── Sales_Projects
```

---

## Permissions Configuration

| Folder | Allowed Group | Access |
|------|------|------|
| HR_Projects | HR_Group | Full Control |
| IT_Projects | IT_Group | Full Control |
| Finance_Projects | Finance_Group | Full Control |
| Sales_Projects | Sales_Group | Full Control |

Users can only access their own department folders.

Examples:
- HR users cannot see IT folder
- Finance users cannot access Sales resources

---

## Features Implemented

- Active Directory domain environment
- Organizational Unit management
- Department-based user creation
- Security group management
- NTFS permission control
- Departmental file server access

---

## Skills Demonstrated

- Active Directory Administration
- Organizational Unit Design
- Security Group Implementation
- NTFS & Share Permissions
- Enterprise Resource Access Control
