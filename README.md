<h1>Network Packet Analysis: DNS and ICMP Logs</h1>

<h2>Description</h2>
This project is dedicated to showcasing proficiency in identifying ICMP (Internet Control Message Protocol) packets within network communication. ICMP packets are integral to understanding network behavior.
<br />



<h2>Program walk-through:</h2>
In a fictional scenario involving a simulated DDoS (Distributed Denial of Service) attack on a company, this project delves into the realm of incident response and cybersecurity analysis. As the designated cybersecurity analyst for the imaginary company, the focus was on investigating and mitigating the impact of the DDoS attack.
<p align="center">
<b>Image and Explanation: </b><br/>
<img src="https://i.imgur.com/Q0c9qzL.png" height="80%" width="80%" alt="Replit Image"/>

The UDP protocol reveals that the DNS server is down or unreachable. As
evident by the results of the network analysis, the ICMP echo reply returned
the error message “udp port 53 unreachable,” Port 53 is commonly used for
DNS protocol traffic. Likely, the DNS server is not responding.
In the resulting log file, 


I
found that DNS port 53 was unreachable. The next step is to identify whether
the DNS server is down or traffic to port 53 is blocked by the firewall. The DNS
server might be down due to a successful Denial of Service attack or a
misconfiguration.
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
