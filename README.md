# Analyzing Packet Captures
## Objective
The Coursera Google Cybersecurity Professional Certification Course work provides practical cybersecurity skills. This guided project utilizes a virtual machine environment to familiarize cybersecurity professionals with the Linux CLI-enabled TCPDump packet analyzer and packet capture methodology. The project analyzes a sample .pcap file. Specfically, this project explores methodologies to identify available interfaces, generate packet capture files, and analyze HTTP packet captures.

### Skills Learned
-Packet capture methodologies
<p>-TCPDump switches</p>
<p>-generate packet capture files</p>

### Tools Used
-Laptop
<p>-Linux CLI-enabled TCPDump packer analyzer</p>
<p>-Coursera Google Cybersecurity Professional Certification</p>

### Steps
<img src="https://i.imgur.com/jMzVO1j.png" style="width: 100%;" alt="1">
<p><i>Ref 1: Discovering interfaces to conduct packet capture</i></p>
<img src="https://i.imgur.com/odnHQjg.png" style="width: 200%;" alt="1">
<p><i>Ref 2: Interface, port, number of captures, and export file designated, while script is prompted to run in the background and not resolving names, simlariy website opening and export .pcap information is displayed </i></p>
<img src="https://i.imgur.com/UJcMTKy.png" style="width: 100%;" alt="1">
<p><i>Ref 3: Export file read with verbose option</i></p>
<p><b>Significant takeaways for the packet header information:</b></p>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<table border="1">
  <tr>
    <th>Element</th>
    <th>Examples</th>
    <th>Examples</th>
    <th>Examples</th>
    <th>Examples</th>
  </tr>
 <tr>
    <td>TTL</td>
    <td>64 (Linux)</td>
    <td>126 (128 is Windows)</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>TOS</td>
    <td>0x0 (default)</td>
    <td>0x60 (CS3)*</td>
    <td>0x80 (CS4)**</td>
    <td></td>
  </tr>
  <tr>
    <td>Flags</td>
    <td>[P.] (Push data)</td>
    <td>[.] (ACK)</td>
    <td>[S.] (SYN/ACK)</td>
    <td>[F.] (FIN/ACK)</td>

  </tr>
</table>

</body>
</html>
<p><i>*CS3 class selector 3; broadcast video</i> (1)</p)>
<p><i>**CS4 class selector 4; real-time interactive</i> (1)</p>
<img src="https://i.imgur.com/bcsBpDP.png" style="width: 100%;" alt="1">
<p><i>Ref 4: Hexadecimal and ASCII code is generated to view for anomalies </i></p>

### References
(1) Configuration Guidelines for DiffServ Service Classes. https://datatracker.ietf.org/doc/html/rfc4594.
