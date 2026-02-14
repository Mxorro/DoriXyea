
# DoriXyea – TCP Connect Flood Demo (GUI)

Educational TCP half-open / full-connect flood tool written in Go with Fyne GUI.

**Purpose:**  
Demonstration of how many simultaneous TCP connections a single machine can open and how it affects target systems (e.g. local router, test server).  

**NOT for malicious use** – only for learning networking, stress-testing own infrastructure, or CTF/red-team exercises with permission.

**Capabilities:**
- Target: any IP/host + port (TCP)
- Threads: adjustable 100–5000
- Packet payload size: 1 KB – 10 MB per connection
- Live upload speed display (Mb/s)
- Clean Start/Stop control

**Tech stack:**
- Go (golang.org)
- Fyne GUI toolkit (fyne.io)
- net.DialTimeout for connections

**Disclaimer:**
This tool can consume significant network and CPU resources.  
Use only on hardware/networks you own or have written permission to test.  
Any illegal use is your responsibility.

Compiled binary for Windows x64 (no dependencies).
Source code available in this repo.

Have fun responsibly.
