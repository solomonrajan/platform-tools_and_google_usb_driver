# platform-tools_and_google_usb_driver
PowerShell Script for download and config platform-tools and Google USB Driver as Environment Variable in Windows.

 1. Run PowerShell as Administrator 
 2. Execute the following commands
 
```
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/solomonrajan/platform-tools_and_google_usb_driver/main/adb-usb-driver.ps1" -OutFile "C:\adb-usb-driver.ps1"
```
```
Powershell.exe -ExecutionPolicy RemoteSigned -File  "C:\adb-usb-driver.ps1"
```

 3. Go to Windows Update and check for "Optional Updates"
 4. Done.
