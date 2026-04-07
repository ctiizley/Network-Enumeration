<h1>Multi Host Network Enumeration</h1>

 

<h2>Description</h2>
This lab focused on conducting full-scale network enumeration against multiple hosts within an isolated virtual lab environment. The objective was to identify active devices, perform full TCP SYN scans, detect service versions, and fingerprint operating systems across different platforms.
<br />


<h2>Tools Used </h2>

- <b>arp-scan</b>
- <b>hping</b>
- <b>nmap</b>
- <b>wireshark</b>

<h2>Program walk-through:</h2>
🔎 Phase 1: Host Discovery
<p align="center">
Used ARP scanning to identify active devices on the local network without relying on ICMP responses: <br/>
<img src="https://i.imgur.com/MMvuYlC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left">
🌐 Phase 2: Full TCP SYN Scan <br/>
<p align="center">
Performed a full port scan to identify open ports and detect exposed services on the target system: <br/>
<img src="https://i.imgur.com/QpSzSGl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left">
⚙️ Phase 3: Service Version Detection <br/>
<p align="center">
Enumerated active services and identified software versions running on open ports.
<br/>
<img src="https://i.imgur.com/54JmfQz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left">
🖥️ Phase 4: Operating System Detection <br/>
<p align="center">
Estimated the operating system using TCP/IP fingerprinting based on network response behavior.
<br/>
<img src="https://i.imgur.com/8upkeWg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>📊 Key Takeaways </h2>

- <b>Identified live hosts using Layer 2 scanning</b>
- <b>Discovered open ports and exposed services</b>
- <b>Detected service versions for analysis</b>
- <b>Performed OS fingerprinting using network characteristics</b>

<h2>🧠 Skills Demonstrated </h2>

- <b>Network discovery</b>
- <b>Port scanning and analysis</b>
- <b>Service enumeration</b>
- <b>OS fingerprinting</b>
- <b>Command-line tool usage</b>


<h2>Description</h2>
All activities were conducted in an isolated lab environment on authorized systems for educational and defensive security purposes only.
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

