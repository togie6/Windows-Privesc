

# Windows-Privesc

Introduction into windows privilege escalation

Presented by me at Sectalks BNE0x19 (26th Session)  
Created this presentation to force myself to learn a topic which I struggled with.


Unfortunately I did not get the time to incorporate all my ideas before the presentation. However I will be looking at adding to this in the near future.


## Content

### Password mining
  &gt; Files

  &gt; SAM/Unattended/sysprep

  &gt; Registry


### AlwaysInstallElevated

### Services

  &gt; Weak File Permissions

  &gt; Weak Registry Permissions

  &gt; Unquoted Service Paths

  &gt; DLL Hijacking

### Kernal exploits

  &gt; Finding an exploit

  &gt; Compiling exploits

### Post Exploitation

  &gt; Mimikatz

### Automation

  &gt; Windows-privesc-check

### Other

  &gt; Powersploit



## Tools

creddump                    -&gt; https://tools.kali.org/password-attacks/creddump

ICACLS  -&gt; Built into windows

Accesschk            -&gt; https://docs.microsoft.com/en-us/sysinternals/downloads/accesschk

Windows-exploit-suggester  -&gt; https://github.com/GDSSecurity/Windows-Exploit-Suggester

Mimikatz              -&gt; https://github.com/gentilkiwi/mimikatz/

Windows-Priv-Check   -&gt; https://github.com/pentestmonkey/windows-privesc-check

Powersploit     -&gt; https://github.com/PowerShellMafia/PowerSploit



## Sources

http://www.tenable.com/sc-report-templates/microsoft-windows-unquoted-service-path-vulnerability

http://blog.opensecurityresearch.com/2014/01/unsafe-dll-loading-vulnerabilities.html

https://www.exploit-db.com/docs/31687.pdf

http://travisaltman.com/windows-privilege-escalation-via-weak-service-permissions/

http://www.primalsecurity.net/0x4-python-tutorial-exe/

http://blog.opensecurityresearch.com/2014/01/unsafe-dll-loading-vulnerabilities.html

https://pentestlab.blog/2017/03/27/dll-hijacking/

https://www.exploit-db.com/papers/14813/

https://msitpros.com/?p=2012

https://blog.rapid7.com/2015/12/21/scannow-dll-search-order-hijacking-vulnerability-and-deprecation/

