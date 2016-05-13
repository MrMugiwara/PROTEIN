PROTEIN - PROTEct your INformation
 
.SYNOPSIS
- This script is an active monitoring for files in a repository to search for known or unknown ransomware.
- PROTEIN captures the action of the creation of new files, analyzing them and determining whether they are valid or not for the corporation.
- PROTEIN Identifies known files (whitelist), potential threats (blacklist) likewise unknown files for further processing.
- PROTEIN logs every creation action on files on your server.
- Possibility to email alerts to an administrator when a new ransomware is detected.
- PROTEIN alerts, via messagebox on the user's computer, when a new ransomware is detected.
- PROTEIN disables domain's user affected by the ransomware, preventing the access to the repository by the ransomware or other critical objects of the system.
- PROTEIN disables the NIC on the user's computer affected by the ransomware, to block the access to the network.

.REQUIREMENTS
- Run this script as an administrator to control computers and domain users remotely.

.INSTALATION
- ./protein.ps1 --install
- ./protein.ps1 --configure

.NOTES
- Author		: Amador Pérez Trujillo
- Twitter		: @c0p3rnic0
- Company		: http://www.newvisionsoftlan.com

	
.PARAMETER --install
- Set the folder path to monitor, path and filename for store logs and adminsitrator's email to alert of a risk.
- IMPORTANT!!! Anti_malware_config folder MUST BE in c:\ on your File Server

.PARAMETER --monitor
- Start monitoring the Folders... Start the Game!!!

.PARAMETER --configure
- Re-configure path of folders to monitor and store the logs, email address..

.PARAMETER --path
- Show by console the configuration files for checking purposing.

.PARAMETER --logs
- Show by console the log file.
