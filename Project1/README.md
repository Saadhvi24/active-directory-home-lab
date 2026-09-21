# Project 1 — Active Directory Home Lab

## Overview

Built a hands-on Active Directory home lab using Windows Server 2022, Windows 11, and Oracle VirtualBox.

The lab demonstrates basic Windows domain administration, user and group management, Organizational Units, DNS, domain joining, and file-sharing permissions.

## Environment

- Windows Server 2022 — Domain Controller
- Windows 11 — Domain-joined workstation
- Oracle VirtualBox
- Active Directory Domain Services
- Domain: `savitech.local`

## Implementations

### 1. Active Directory Domain

Configured a Windows Server 2022 Domain Controller and created the `savitech.local` Active Directory domain.

### 2. Organizational Units

Created OUs to organize users and computers, including:

- IT
- HR
- Finance
- Sales
- Servers
- Workstations
- Security Groups
- Service Accounts

### 3. User and Group Management

Created domain users and security groups and practiced:

- User creation
- Password resets
- Account enable/disable
- Account unlocking
- Group membership
- Moving users between OUs

### 4. Domain-Joined Workstation

Joined a Windows 11 workstation to the `savitech.local` domain and verified domain authentication.

### 5. File Sharing and Permissions

Configured a shared folder using:

- NTFS permissions
- Network share permissions
- Security groups for access control

### 6. DNS and Troubleshooting

Configured and verified DNS for the Active Directory environment.

Troubleshooting included checking network connectivity, DNS resolution, Domain Controller discovery, and authentication dependencies.

## Troubleshooting Approach

I learned to troubleshoot by following system dependencies:

1. Identify what I am trying to accomplish.
2. Identify what it depends on.
3. Find which dependency is not working.
4. Verify the configuration.
5. Test the result.

For example, when troubleshooting domain connectivity, I checked the network connection first, then DNS, and finally Domain Controller discovery.

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
