# IOC Report: Hydraq Indicators

## Summary

Hydraq is on of the pieces of malware used by GLASS WIZARD on high importance targets. The following indicators may be useful for identifying malicious activity.

## Indicators

| Indicator | Context | Notes |
|:----------|:--------|:------|
| Rasmon.dll | file name | |
| Securmon.dll | file name | |
| A0029670.dll | file name | |
| AppMgmt.dll | file name | |
| HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\RaS[% random 4 chars %] | Malware reg key. | Space removed before random chars.  |
| %System%/acelpvc.dll | Secondary File | Not a definitive indicator. |
| %System%/VedioDriver.dll | Secondary File | Not a definitive indicator. |
| RaS[FOUR RANDOM CHARACTERS] | Service Name | May have false positives as a result. |
| yahooo.8866.org | C2 Domain | |
| sl1.homelinux.org | C2 Domain | |
| 360.homeunix.com | C2 Domain | |
| li107-40.members.linode.com | C2 Domain | |
| ftp2.homeunix.com | C2 Domain | | 
| update.ourhobby.com | C2 Domain | |
| blog1.servebeer.com | C2 Domain | |

_Notes:_
- Inactive domains are set to loopback (127.0.0.2).
- Symantec also had information about network traffic indicators.

## Related TTPs

Actions the Hydraq malware is capable of.

- Escalate process priviledges.
- Shutdown or reboot the system.
- Read, write, execute, copy, change attributes of, and delete files.
- Execute commands via cmd.exe.
- Download additional components.
- Modify the system registry.
- List local resources (Drives, services etc.)
- Modify the local filesystem.
- Self update.
- Adjust token privileges.
- Check status, control, and end processes and services.
- Create, modify, and delete registry entries.
- Restart and shut down the computer.
- Gather information about the victims machines.
- Clear all system event logs.
- Download a remote file, save it as %Temp%\mdm.exe, and then execute it.


## References

- https://home.mcafee.com/virusinfo/virusprofile.aspx?key=253416
- https://www.symantec.com/connect/blogs/trojanhydraq-incident https://www.symantec.com/connect/blogs/trojanhydraq-incident 

