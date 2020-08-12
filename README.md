# habitat-windows-workstation
Instructions for setting up a Windows 10 Habitat Workstation

## Chocolately
Chocolately is installed first to enable the easy install of other components.

1. Launch Windows Powershell as administrator.
2. Run `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`
3. Type `choco` to confirm install. You should see the verison number and a short message.

## Visual Studio Code
We will need a code editor. Visual Studio Code is free and excellent. From your existing Administrative Shell, run `choco install vscode`

## Git
Code should be managed in a repository. We will manage this using Git. Run `choco install git`

## Habitat
Run `choco install habitat`

## Setup Habitat
Run `hab setup`

## Install Studio
Run `hab studio enter`




