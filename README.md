# Microsoft Office LTSC Professional Plus 2021

[Click here to download zip file](https://github.com/MsTerious2000/ms-office-pro-plus-2021/archive/refs/heads/main.zip)

## INSTALLATION
1. Open command prompt as administrator
2. Go to directory of configuration.xml file
3. Run the following command

```
setup /configure configuration.xml
```
4. After the installation is complete, proceed to Activation.

## ACTIVATION
1. Open command prompt as administrator
2. Run the following commands
```
cd /d %ProgramFiles%\Microsoft Office\Office16
```
```
for /f %x in ('dir /b ..\root\Licenses16\ProPlus2021VL_KMS*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
```
```
cscript ospp.vbs /setprt:1688
cscript ospp.vbs /unpkey:6F7TH >nul
cscript ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH
cscript ospp.vbs /sethst:107.175.77.7
cscript ospp.vbs /act
```
