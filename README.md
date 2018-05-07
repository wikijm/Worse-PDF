# Worse-PDF
Turn a normal PDF file into malicious.Use to steal Net-NTLM Hashes from windows machines.

### Compatibility
| Name | Version | Release | Compatibility | Tested by
| :--------------: | :--------------: | :--------------: | :--------------: | :--------------:
| Windows 10 Professional | 10.0.16299.371 (WinBuild.160101.0800) | 1709 | :white_check_mark: | @wikijm



How to get OS information:
- Name:     Get-WmiObject -Class Win32_OperatingSystem | ForEach-Object -MemberName Caption
- Version:  (Get-ItemProperty -Path c:\windows\system32\hal.dll).VersionInfo.FileVersion
- Release:  (Get-ItemProperty -Path "HKLM:\SOFTWARE\Microsoft\Windows NT\CurrentVersion" -Name ReleaseId).Release
Id

Reference :

    https://research.checkpoint.com/ntlm-credentials-theft-via-pdf-files/
    https://github.com/deepzec/Bad-Pdf

By: 3gstudent

License: BSD 3-Clause

To do:

- Fix Cross-reference table
