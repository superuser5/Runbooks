# Protocol - SMB & Netbios

SMB versions:

* SMB1 – Windows 2000, XP and Windows 2003
* SMB2 – Windows Vista SP1 and Windows 2008
* SMB2.1 – Windows 7 and Windows 2008 R2
* SMB3 – Windows 8 and Windows 2012

```rpcclient -U "" <target>```

Manual check for null sessions

```nbtscan ```

Scan network for Netbios name information

```enum4linux -a <target>```

Enumerate Windows hosts

```smbmap -H <target>```

Scan for open SMB shares
