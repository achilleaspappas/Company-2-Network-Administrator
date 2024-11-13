# Company 2 - Network Administrator
This repository contains automation scripts developed by me based on my experience working at a company under NDA. Please note that the scripts and content in this repository are not officially endorsed or approved by any company, and are shared here for educational and personal use only. Due to an NDA, specific details related to the company and its internal systems are not disclosed.

## Contents
- **Backup Scripts**: Bash and python scripts for automating system, database, network device backups, including configurations for Fortinet and Cisco devices.
- **Windows Config Script**: A PowerShell script that simplifies the initial setup and configuration for new Windows PCs.

## Prerequisites
To utilize these scripts effectively, ensure the following:
- **Backup Scripts**:
  - [Python 3](https://www.python.org/downloads/) 
  - SMB/CIFS share access on your network for storing backup files
  - Logging paths correctly set up according to your environment
- **Windows Config Script**:
  - [PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4)
  - Administrative privileges for running configurations on new PCs
  - Active Directory credentials for joining the domain

## Getting Started
1. **Clone the Repository**: ```git clone https://github.com/achilleaspappas/Company-2-Network-Administrator.git```
2. **Backup Scripts**:
    * Navigate to the backup-scripts folder.
    * Review and modify paths as necessary in each script to match your environment.
    * Execute the backup.sh script as a cron job or manual backup.
3. **Windows Config Script**:
    * Navigate to the windows-config-script folder.
    * Run windows-config.ps1 in PowerShell with administrator rights.
    * Follow the menu prompts to apply desired configurations on the new PC.
    
## Authors
[Achilleas Pappas] - Created the scripts.

## License
This project is provided as-is for personal use and development. Due to the terms of a non-disclosure agreement (NDA), redistribution is not permitted.

## Acknowledgments
This project was developed as part of my personal work and experience. Due to non-disclosure agreements (NDAs), specific details related to any company or organization cannot be disclosed.
