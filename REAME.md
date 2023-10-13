# Active Directory Setup

1. Use SConfig to:
    - Change the hostname
    - Change the IP address to static (had to reboot Sever and WS after this, WS wasn't resolving)
    - Change the DNS server to our own IP address

2. Install the Active Directory Windows Feature

```
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```