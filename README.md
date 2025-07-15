# ctf
CTF-related information

## Tools
### crackmapexec
URL https://www.kali.org/tools/crackmapexec/
Pentesting Windows/Active Directory environments.
From enumerating logged on users and spidering SMB shares to executing psexec style attacks, auto-injecting Mimikatz/Shellcode/DLL’s into memory using Powershell, dumping the NTDS.dit and more.

Examples: 
List Windows Shares of a given IP using guest access
`cme smb 192.168.1.100 -u 'doesnotexist' -p '' --shares`

## Recoinessance
### Windows Shares
