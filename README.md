# Analyzing Packet Captures
## Objective
The Coursera Google Cybersecurity Professional Certification Course work provides practical cybersecurity skills. This guided project utilizes a virtual machine environment to familiarize cybersecurity professionals with the WireShark network protocol analyzer GUI and packet capture analysis methodology. The project analyzes a sample .pcap file. Specfically, this project explores methodologies to potentially discover data exfiltration.

### Skills Learned
-Data exfiltration methodologies
<p>-WireShark display filter commands:</p>
<p>--by IP Address (ip.addr == ...)</p>
<p>--by source IP Address (ip.src == ...)</p>
<p>--by destintation Address (ip.dst == ...)</p>
<p>--by MAC address (eth.addr ==...)</p>
<p>--by DNS packets (udp.port == 53)</p>
<p>--by TCP packets (tcp.port == 80)</p>
<p>-by TCP traffic with text data (tcp contains "curl")</p>
<p>-WireShark display filter operators (==. contains, etc.)
<p>-Packet capture analysis:</p>
<p>--Destination IP address</p>
<p>--Arrival time</p>
<p>--Header Length</p>
<p>--Frame length</p>
<p>--MAC address</p>
<p>--Internal protocol</p>
<p>--Time to live</p>
<p>--TCP containing text data</p>

### Tools Used
-Laptop
<p>-WireShark network protocol analyzer GUI</p>
<p>-Coursera Google Cybersecurity Professional Certification</p>

### Steps
<img src="https://i.imgur.com/odnHQjg.png" style="width: 100%;" alt="1">
<p><i>Ref 1: </i></p>
<img src="https://i.imgur.com/jMzVO1j.png" style="width: 100%;" alt="1">
<p><i>Ref 2: </i></p>
<img src="https://i.imgur.com/s6tC3kv.png" style="width: 100%;" alt="1">
<p><i>Ref 3: </i></p>
<img src="https://i.imgur.com/bcsBpDP.png" style="width: 100%;" alt="1">
<p><i>Ref 4: </i></p>
<img src="https://i.imgur.com/UJcMTKy.png" style="width: 100%;" alt="1">
<p><i>Ref 5: </i></p>
