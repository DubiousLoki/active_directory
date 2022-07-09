# 01 Installing Domain Controller

1. Use 'scconfig' to:
    - change the hostname
    - change the ip address to static
    - change the dns server to our own ip address


2. Install the Active Directory Windows Feature

``` shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```