# Setup GCPW on a new window device using a powershell script

## How to run a script
+ Before you can run a script on Windows, you need to change the default PowerShell execution policy. Execution policy does not apply to PowerShell running on non-Windows platforms.

- On the powershell
```
Set-ExecutionPolicy AllSigned
```
or 
```
Set-ExecutionPolicy RemoteSigned
```
- To run a script, type the full name and the full path to the script file.
```
C:\Scripts\SetUpGCPW.ps1
```


