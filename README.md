# elevate-labs-task-1
Scanning Local Networks for Open Ports

To scan for open ports on the local network, we will use tools like Nmap and Wireshark. It is essential to remember that we should only scan our own servers or networks; scanning other servers or websites without authorization is illegal.

Nmap:
Nmap, which stands for Network Mapper, is a free, open-source command-line tool used for information gathering and reconnaissance. It scans hosts and services on a computer network by sending packets and analyzing the responses.

To begin, open the Command Prompt and use the command `ipconfig` to find your IP address.
 Next, install Nmap, which is readily available online, and complete the setup. 
After acquiring the target IP address, paste it into Nmap and start the scanning process. 
There are different scanning profiles available, such as Intense Scan, All TCP Ports, Quick Scan, and more. During my intense scan, I discovered four open ports, while the All TCP Ports scan revealed fifteen open ports.

Note: It is important to regularly check for open ports and close any unnecessary ones to prevent potential hacking.

Wireshark: 
Wireshark is a software tool used to monitor network traffic through a network interface. It is one of the most widely used network monitoring tools today, appreciated by system administrators, network engineers, network enthusiasts, network security professionals, and even cybercriminals.

Like Nmap, you can download and install Wireshark from the web. Once set up, the interface will display the different networks connected to your system and the traffic on each. 
You can select the network you wish to analyze. The upper pane shows the source address (both IPv4 and IPv6), destination address, source and destination ports, the protocol to which each packet belongs, and additional packet information.

Through this scanning process, you can gather detailed information about the servers you enter, and it can help identify phishing or unsecured links.

Note:Always visit websites that use the HTTPS protocol for secure browsing.


