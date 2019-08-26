# new_pc_setup

```
# Install Chocolatey
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
# Disable confirmations
choco feature enable -n allowGlobalConfirmation
# Run the apps_to_install.ps1 script which specifies what applications to install
iex ((new-object net.webClient).DownloadString('https://raw.github.com/sai-inampudi/new_pc_setup/master/apps_to_install.ps1'))
```
