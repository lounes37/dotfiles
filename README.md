# Dotfiles

Install chezmoi and your dotfiles from your GitHub dotfiles repo on a new, empty machine with a single command:

## Install chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco install -y git.install chezmoi
```

## Linux
```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply lounes37
```
