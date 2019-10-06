# PowerShellPreferences
includes useful(?) powershell modules

## extract directory
%UserProfile%\My Documents\WindowsPowerShell\profile.ps1

## set execution policy to load .ps1 files
if 
$Get-ExecutionPolicy
> Restricted
then
$Set-ExecutionPolicy RemoteSigned
