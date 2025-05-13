# Check Your PowerShell Version

You can check which version of PowerShell you're running using the following commands.

So, if you want to upgrade to the latest version of the powershell this is the link:
https://github.com/PowerShell/PowerShell/releases

## 📌 For Windows PowerShell

Run this in **Command Prompt** or **Windows PowerShell**:

```powershell
powershell $PSVersionTable.PSVersion
```
💻 Output should be something like this:
```
Major  Minor  Build  Revision
-----  -----  -----  --------
5      1      26100  3912
```
and for the updated powershell this is the command,
```
pwsh -command "$PSVersionTable.PSVersion"
```
💻 Output should give you something like this:
```
Major  Minor  Patch  PreReleaseLabel BuildLabel
-----  -----  -----  --------------- ----------
7      4      10
```

## 🧑‍💻Check out the screenshot
![image](https://github.com/user-attachments/assets/f809078e-7e34-4364-a0e4-5ed0496356b7)
*Here both the version of powershell are present in windows 11*
