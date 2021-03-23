# windows.cfg
1. Install chocolatey:

As admin powershell:
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
2. Restart the shell
3. Windows Terminal: 
`choco install microsoft-windows-terminal`
---
*Where did the good ol' win7 go :(*
