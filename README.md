# Winfiles
My Windows files and configs for productivity.  

## Settings
AutoHotkey  
New-Item -Path "C:\Users\user\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\ahk.ahk" -ItemType SymbolicLink -Value "D:\Program Files\Winfiles\ahk.ahk"
PowerShell  
New-Item -Path "C:\Users\user\Documents\WindowsPowerShell\profile.ps1" -ItemType SymbolicLink -Value "D:\Program Files\Winfiles\profile.ps1"
ConEmu  
New-Item -Path "C:\Program Files\ConEmu\ConEmu.xml" -ItemType SymbolicLink -Value "D:\Program Files\Winfiles\ConEmu.xml"
Windows Terminal  
New-Item -Path "C:\Users\user\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -ItemType SymbolicLink -Value "D:\Program Files\Winfiles\settings.json"

## Archive
Shutdown shortcut (Target: "C:\Windows\System32\shutdown.exe -s -t 600")  
AutoKey for linux  
Notepad++ (config.xml)
