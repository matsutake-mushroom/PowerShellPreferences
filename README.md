# PowerShellPreferences
includes useful(?) powershell modules

## extract directory
%UserProfile%\My Documents\WindowsPowerShell\profile.ps1

## set execution policy 
proper execution policy is needed to load .ps1 files, so
if 
$Get-ExecutionPolicy
> Restricted

then
$Set-ExecutionPolicy RemoteSigned
