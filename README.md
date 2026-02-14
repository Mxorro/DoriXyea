
# DoriXyea – TCP Connect Flood Demo (GUI)
My first project DoriXyea 1.0
Educational TCP half-open / full-connect flood tool written in Go with Fyne GUI.

**Purpose:**  
Demonstration of how many simultaneous TCP connections a single machine can open and how it affects target systems (e.g. local router, test server).  

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

Compiled binary for Windows x64 (no dependencies).
Have fun responsibly.
