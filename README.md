# accesschk.exe
Older version of `accesschk.exe` which supports CLI EULA acceptance.

This can be used for privilege escalation of `Windows XP SP0/1` targets by exploiting the `upnphost` and `SSDPSRV` Windows services.

```powershell
accesschk.exe /accepteula
```

More information about exploitation can be found [here](https://sohvaxus.github.io/content/winxp-sp1-privesc.html).
