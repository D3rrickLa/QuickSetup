# ⚡ QuickSetup

A personal repository to store my favorite `winget` commands and other scripts for quickly reinstalling essential apps and tools on a fresh Windows setup.

## 🛠 Purpose

This repo acts as a lightweight recovery kit for my development environment. Whenever I need to reset or configure a new machine, I can run these commands to get back up and running fast—without the bloat.

## 📦 What's Included

- `install.ps1`: A PowerShell script containing all my `winget` install commands.
- A curated list of apps I actually use—no unnecessary extras.
- `configuration-Office365-x64.xml`: A XML script for essential office products meant to be used with the Office Deployment Tool executable.

## 🚀 Usage

To run the powershell setup script:

```powershell
.\install.ps1
```

To run the XML office script (setup.exe not included, can be downloaded from Microsoft):
```
.\setup.exe /configure .\configuration-Office365-x64.xml
```

## Sample Apps
Below are the apps included in the PowerShell script
- 1Password
- Git
- Mozilla Firefox (Developer version)
- Visual Studio Code
- Neovim
- 7Zip
- Postman
- PowerToys
- VLC
- Revo Uninstaller
- PowerShell
- WinDirStat
- WinSCP
