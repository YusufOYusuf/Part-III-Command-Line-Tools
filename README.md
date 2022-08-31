<h1>Part III: Command Line Tools</h1>



<h2>Description</h2>
In this lab, I learned to use the dig, tcpdump, and nmap commands. The dig command resolves an FQDN (fully qualified domain name) to an IP (Internet Protocol) address on UNIX (Uniplexed information computing system) hosts. The tcpdump command allows a user to display TCP/IP (Transmission Control Protocol/Internet Protocol) and other packets being transmitted or received over a network to which the computer is attached. nmap is a management tool that permits the scanning of a network for hosts and services.


<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux Rolling</b> 


<h2>Languages and Utilities</h2>

- <b>Terminal<b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar open up Terminal: <br/>
<img src="https://i.postimg.cc/Y9NcCxZ3/Screen-Shot-2022-08-31-at-11-31-10-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br>
Type in "dig" command and any website you wish (I choose to ping www.google.com):<br>
<img src="https://i.postimg.cc/fbp2Q0bv/Screen-Shot-2022-08-31-at-11-32-39-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Now I will try the "tcpdump -i eth0 > captured_packets.txt" command to capture packets from a specific interface (tip: press ctrl+c to stop):</br>
<img src="https://i.postimg.cc/44V8j5hL/Screen-Shot-2022-08-31-at-11-36-52-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Now lets try the "cat captured_packets.txt" command to display captured packets on a specific interface:  <br/>
<img src="https://i.postimg.cc/m2JMyxmt/Screen-Shot-2022-08-31-at-11-39-29-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />


<br />
Now I will try the "nmap 192.168.122.1" command to scan for live hosts, operating systems, packet filters, and open ports :  <br/>
<img src="https://i.postimg.cc/02KgBm0c/Screen-Shot-2022-08-31-at-11-41-31-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
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
