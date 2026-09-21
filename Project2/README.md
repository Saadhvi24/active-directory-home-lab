# Project 2 — Advanced Group Policy Lab

## Overview

Built and configured advanced Group Policy settings in a Windows Server 2022 Active Directory lab environment.

The project focused on centralized security and system management using Group Policy.

## Objectives

- Configure and manage Group Policy Objects (GPOs)
- Apply USB device restrictions
- Configure Windows LAPS for local administrator password management
- Link GPOs to the appropriate organizational units
- Verify and troubleshoot Group Policy configuration

## Technologies

- Windows Server 2022
- Windows 11
- Active Directory Domain Services
- Group Policy Management
- Windows LAPS
- Oracle VirtualBox

## Implementations

### 1. Group Policy Management

Created and managed custom GPOs and linked them to the appropriate organizational units.

### 2. USB Device Restrictions

Configured a GPO to restrict USB storage devices using the `USBSTOR` registry setting.

The registry value was configured as:

`Start = 4`

### 3. Windows LAPS

Configured Windows Local Administrator Password Solution (LAPS) to manage the local Administrator account password and back up the password to Active Directory.

Verified successful password retrieval from Active Directory using PowerShell.

## Troubleshooting

Troubleshooting followed a dependency-based approach:

1. Identify what I was trying to accomplish.
2. Identify what the configuration depends on.
3. Determine which dependency was not working.
4. Verify the configuration.
5. Test the result.

## Screenshots

- `p2-01-group-policy-overview.png` — Group Policy environment
- `p2-02-usb-restriction-gpo.png` — USB restriction GPO
- `p2-03-usb-restriction-registry-setting.png` — USBSTOR registry configuration
- `p2-04-laps-gpo-overview.png` — LAPS GPO
- `p2-05-laps-password-retrieval.png` — LAPS password retrieval verification

> Note: The actual LAPS password is intentionally hidden in the screenshot for security.
