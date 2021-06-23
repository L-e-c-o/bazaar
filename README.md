# Bazaar

Bazaar is a place to share miscellaneous links related to cybersecurity and more.
  
Table of Contents
=================

* [Pentest](#-pentest)
* [Red Team](#-red-team)
* [Cobalt Strike](#-cobalt-strike)
* [Linux](#-linux)
* [Offensive programming](#-offensive-programming)
* [Talks](#-talks)
* [Misc](#-misc)

## [↑](#table-of-contents) Pentest

* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) : A list of useful payloads and bypasses
* [Hack Tricks](https://book.hacktricks.xyz/) :  Typical flow that you should follow when pentesting one or more machines
* [GTFOBins](https://gtfobins.github.io/) : List of Unix binaries that can used to bypass local security restrictions
* [LOLBAS](https://lolbas-project.github.io/) : Similar to GTFOBins but for Windows binary's 
* [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) :  FuzzDB contains comprehensive lists of attack payload primitives for fault injection testing
* [Hackndo](https://beta.hackndo.com/kerberoasting/) : A very detailled blog covering somes Actives Directory's attacks
* [Hashcat cheatsheet](https://github.com/frizb/Hashcat-Cheatsheet) : Hashcat Cheatsheet for OSCP

## [↑](#table-of-contents) Red Team

* [Awesome Red Teaming](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming) :  List of Awesome Red Team resources
* [Chimera](https://github.com/tokyoneon/Chimera) : PowerShell Obfuscation Script Designed To Bypass AMSI And Antivirus Solutions
* [C2 - shad0w](https://github.com/bats3c/shad0w) : A post exploitation framework designed to operate covertly on heavily monitored environments
* [C2 - Sliver](https://github.com/BishopFox/sliver) : Cross-platform (Go) adversary simulation/red team platform
* [Shellcode delivery through ICMP](https://blog.romanrii.com/using-icmp-to-deliver-shellcode) : Article about using ICMP for shellcode delivery
* [Antivirus Artifacts](https://github.com/D3VI5H4/Antivirus-Artifacts) : List of API hooks by major antiviruses
* [iRed.team](https://www.ired.team/) : Great Red Team resources with lot of techniques
* [AMSI.fail](https://amsi.fail/) : Generates obfuscated PowerShell snippets that break or disable AMSI for the current process.
* [C2 - SharpC2](https://github.com/SharpC2/SharpC2) : .NET Command & Control Framework by RastaMouse
* [VBA shellcode loader](https://adepts.of0x.cc/alternatives-copy-shellcode/) : 1001 ways to load shellcode in memory from VBA Macro
* [Trigen](https://github.com/karttoon/trigen) : Python script which uses different Win32 function calls in generated VBA to execute shellcode
* [RAT - Koadic](https://github.com/zerosum0x0/koadic) : Windows post-exploitation rootkit similar to other penetration testing tools such as Meterpreter and Powershell Empire
* [Covenant AV Evasion](https://offensivedefence.co.uk/posts/covenant-profiles-templates/) : Using Custom Covenant Listener Profiles & Grunt Templates to Elude AV
* [Phishing Evasion](https://www.bleepingcomputer.com/news/security/phishing-sites-now-detect-virtual-machines-to-bypass-detection/amp/?__twitter_impression=true) : Evade detection by checking whether a website is visited from a virtual machine or headless device.
* [VBA InkPickture execution](https://www.whiteoaksecurity.com/2020-3-11-alternative-execution-a-macro-saga-part-1/) : VBA macro execution on open without classic AutoOpen()
* [Invoke-Stealth](https://github.com/JoelGMSec/Invoke-Stealth) : Simple & Powerful Powershell Script Obfuscator

## [↑](#table-of-contents) Cobalt Strike

* [ScareCrow](https://github.com/optiv/ScareCrow) : Payload creation framework with EDR bypass
* [PEzor](https://github.com/phra/PEzor) : Generate artifacts with defense evasion
* [SharpLAPS](https://github.com/swisskyrepo/SharpLAPS) :  Retrieve the LAPS password from the Active Directory within Cobalt Strike session using execute-assembly
* [Aggressor Assessor](https://github.com/FortyNorthSecurity/AggressorAssessor) : List of useful scripts
* [C2concealer](https://github.com/FortyNorthSecurity/C2concealer) : Random C2 malleable profiles generator
* [Geacon](https://github.com/darkr4y/geacon) : Cobalt Strike's beacon implementation in Go
* [365CS](https://github.com/0e0w/365CS) : Best Cobalt Strike related resources
* [BOF Collection](https://github.com/rvrsh3ll/BOF_Collection) : Collection of useful Beacon Objet Files (BOF)
* [Cobalt Strike BOF](https://github.com/Yaxser/CobaltStrike-BOF) : Another collection of beacon BOF
* [Cobal Strike kits](https://github.com/0xthirteen) : Kits collections repositories
* [Awesome-CobaltStrike](https://github.com/zer0yu/Awesome-CobaltStrike) : List of Awesome CobaltStrike Resources
* [Cobalt-Strike-Cheatsheet](https://github.com/S1ckB0y1337/Cobalt-Strike-CheatSheet) : Some notes and examples for Cobalt Strike's functionality
* [Aggrokatz](https://github.com/sec-consult/aggrokatz/) : Aggrokatz is an aggressor plugin extension for Cobalt Strike which enables pypykatz to interface with the beacons remotely
* [RedWarden](https://github.com/mgeeky/RedWarden) : Cobalt Strike C2 Reverse proxy that fends off Blue Teams, AVs, EDRs

## [↑](#table-of-contents) Active Directory

* [Introduction to Windows tokens](https://www.elastic.co/blog/introduction-to-windows-tokens-for-security-practitioners) Understanding of Windows access tokens

## [↑](#table-of-contents) Linux

* [ewmh-m2m](https://pypi.org/project/ewmh-m2m/) : Python script to move windows from one monitor to a other in Xfce
* [move-to-next-monitor](https://github.com/jc00ke/move-to-next-monitor) : Bash script to move windows from one monitor to the next

## [↑](#tables-of-contents) Offensive programming

* [OffensiveNIM](https://github.com/byt3bl33d3r/OffensiveNim) : Weaponizing Nim for implant development and general offensive operations
* [ConfuserEx](https://github.com/mkaring/ConfuserEx) : An open-source, free protector for .NET applications
* [Abusing native functions](http://ropgadget.com/posts/abusing_win_functions.html) : Abusing native Windows functions for shellcode execution
* [CallObfuscator](https://github.com/d35ha/CallObfuscator) : Obfuscate specific windows apis with different apis
* [OffensiveC#](https://github.com/matterpreter/OffensiveCSharp) : Collection of Offensive C# Tooling
* [Universal Loader](https://github.com/Binject/universal) : Cross plateform shared library loader in Go
* [VM detection in browser](https://vxug.fakedoma.in/papers/VXUG/Mirrors/bannedit.github.io-Virtual%20Machine%20Detection%20In%20The%20Browser.pdf) : Detect if page is visited from a virtual machine
* [Coldfire](https://github.com/redcode-labs/Coldfire) : Golang malware development library
* [Neurax](https://github.com/redcode-labs/Neurax) : A framework for constructing self-spreading binaries
* [Al-Khaser](https://github.com/LordNoteworthy/al-khaser) : Public malware techniques used in the wild (Virtual Machine, Emulation, Debuggers, Sandbox detection)

## [↑](#tables-of-contents) Talks

* [Defence Evasion](https://www.youtube.com/watch?v=CUqKAaHQa14) : Securi-Tay 2020: Offensive Tradecraft - Defence Evasion - Paul Laîné
* [Post exploitation](https://youtu.be/tWQNM2vuQEM?t=333) : Abusing Microsoft Office for Post-Exploitation - Kyle Avery
* [EDR Evasion](https://www.youtube.com/watch?v=LXfhyTpQ7TM) : Defeating EDRs using Dynamic invocation by Jean-Francois Maes

## [↑](#table-of-contents) Misc

* [RFID Proximity Cloning Attacks](https://www.blackhillsinfosec.com/rfid-proximity-cloning-attacks/) : RFID attacks explained in details with examples
* [Skeleton Key](https://pentestlab.blog/2018/04/10/skeleton-key/) : The Skeleton Key is a malware which is stored
* [Invoke-Ngrok](https://github.com/benyG/Invoke-Ngrok) : Expose local port of a remote victim over Internet using Ngrok from Powershell
* [vx-underground](https://vx-underground.org/) : The largest collection of malware source code, samples, and papers on the internet
* [dark vortex](https://0xdarkvortex.dev/) : Blog about Red Team stuff and much more
* [SniperPhish](https://sniperphish.com/) : An open-source phishing toolkit to simulate real-world phishing attacks that comprise phishing email and website
* [BlockTheSpot](https://github.com/mrpond/BlockTheSpot) : Block Spotify ads on Windows
* [spotify-adblock-linux](https://github.com/abba23/spotify-adblock-linux) : Block Spotify ads on Linux
