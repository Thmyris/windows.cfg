# windows.cfg
1. Install chocolatey:

As **admin** powershell:
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
2. Restart the shell

3. Drivers (TODO)

4. Install these programs:
- Windows Terminal: 
`choco install microsoft-windows-terminal`
- Process Hacker 2 (set default)
- 7-zip (set context menu items)
- Git
- Python3
- Pip3
- Java, JDK
- BurpSuite
- Cherrytree
- Notepad++ (set style from the reference image in archive)
- Vivaldi (login)
- Typora
- Atom (https://gist.github.com/Thmyris/de7f0638df46112c5f870e61d5fe77cd)
- Discord
- Slack
- Telegram
- Screen to Gif
- Sandboxie
- Wireshark
- Simple DNS Crypt
- Opera GX
- Lightshot
- Qbittorrent
- F.lux
- OBS-studio
- VirtualCloneDrive
- Bulk Rename Utility
- CCleaner (older version, set settings)
- FastStone Image Viewer
- Fraps (and frafs)
- Handbrake
- Jdownloader 2
- K-lite Codec Pack (older version)
- WinDirStat
- Speccy
- HWInfo64
- paint.net
- Moo0 Video Cutter (older version)
- Moo0 Audio Recorder
- SumatraPDF
- WhoCrashed
- Audacity
- DaVinci Resolve
- LibreOffice
- VLC
- SQLite DB Browser
- QT Designer
- Node
- Mozilla Firefox
- Fastcopy (old version, v330, install for context menu also)
- Fonts & Typefaces folder from my archive
- OpenVPN
- VirusTotal Uploader
- (if nvidia gpu) Nvidia Experience
- (if amd gpu) AMD Relive

3. Set Path for programs:
- Node
- Python
- javac

5. Set Defender exclusion to all drives

6. Copy these portable programs:
- ffmpeg
- Turn Off LCD
- Keyboard Locker
- VeraCrypt
- Backspace goes UP
- F4-is-kill

7. Set $PATH for portables:
- ffmpeg
- Turn Off LCD
- Keyboard Locker
- VeraCrypt
- Backspace goes UP
- F4-is-kill

8. Additional Configuration:
- Disable F1 Help Menu
- Windows 10 - Bloatware Removal via Powershell
- Windows 10 - Old Windows 7 Calculator
- Take Ownership(run as admin)

9. Reboot PC

## Todo:
- Write out all the necessary commands for installing all the programs via CLI. If it's not possible put them in a list for manual installation.
- Put those commands into `.sh` and `.ps1` files and completely automate the process.

---
*Where did the good ol' win7 go :(*
