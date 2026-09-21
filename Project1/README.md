# Project 1 — Active Directory Home Lab

## Overview

A hands-on Active Directory home lab demonstrating Windows Server administration, domain management, user and group management, DNS, domain joining, and file-sharing permissions.

## Lab Environment

- Windows Server 2022 — Domain Controller
- Windows 11 — Domain-joined workstation
- Oracle VirtualBox
- Active Directory Domain Services
- Domain: `savitech.local`

## What I Built

### Active Directory Domain
- Configured Windows Server 2022 as a Domain Controller.
- Created the `savitech.local` Active Directory domain.
- Configured DNS for the domain.

### Organizational Units
Created and organized OUs for:

- IT
- HR
- Finance
- Sales
- Servers
- Workstations
- Security Groups
- Service Accounts

### User and Group Management
- Created domain users.
- Created and managed security groups.
- Reset passwords.
- Enabled and disabled accounts.
- Unlocked accounts.
- Moved users between OUs.
- Managed group membership.

### Domain-Joined Workstation
- Configured a Windows 11 workstation.
- Joined the workstation to the `savitech.local` domain.
- Verified domain authentication.

### File Sharing and Permissions
- Created a shared folder.
- Configured NTFS permissions.
- Configured network share permissions.
- Used security groups to manage resource access.

## Troubleshooting

I used a dependency-based troubleshooting approach:

1. Identify what I am trying to accomplish.
2. Identify what the task depends on.
3. Determine which dependency is failing.
4. Verify the configuration.
5. Test the result.

For example, when troubleshooting domain connectivity, I checked network connectivity, DNS resolution, and Domain Controller discovery.

## Skills Demonstrated

- Active Directory administration
- Windows Server administration
- User and group management
- Organizational Unit management
- DNS fundamentals
- Domain joining
- NTFS and share permissions
- Network troubleshooting
- Virtual machine administration
