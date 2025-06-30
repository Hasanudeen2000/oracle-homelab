# oracle-homelab
Set up a mini Windows network in Oracle VirtualBox

## Overview
A hands-on project to set up a Windows Server 2019 domain controller and Windows 10 client using Oracle VirtualBox.

## Technologies Used
- **Oracle VirtualBox**
- **Windows Server 2019**
- **Windows 10**
- **PowerShell**
- **Active Directory, DHCP, DNS**

## Features
- Automated user account creation via PowerShell
- Multi-adapter networking for internet and internal connectivity
- DHCP and DNS configuration on the domain controller

## Setup Instructions
1. Install Oracle VirtualBox and download Windows Server 2019 and Windows 10 ISOs.
2. Create VMs and configure networking.
3. Install and promote the domain controller.
4. Use the provided PowerShell scripts to automate user creation.

## Usage
Run `userCreation.ps1` to create bulk user accounts in Active Directory.

## Screenshots
![Lab Diagram](screenshots/lab-diagram.png)

