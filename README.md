# Protect-RDSFromBruteforce

[Protect-RDSFromBruteforce.ps1](Protect-RDSFromBruteforce.ps1)

Simple ad-hoc self-defence script for the public accessible RDP servers.
Throw it to Task Scheduler (with SYSTEM privileges)

[Install-ProtectRDSFromBruteforce.ps1](Install-ProtectRDSFromBruteforce.ps1)

Script will install Protect-RDSFromBruteforce.ps1 as scheduled task. You can invoke it from elevated PowerShell session directly:
`Invoke-Expression (Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/al-ign/Protect-RDSFromBruteforce/master/Install-ProtectRDSFromBruteforce.ps1' -UseBasicParsing).Content`
