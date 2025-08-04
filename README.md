# Discover-open-ports-on-device
It discovers the open ports through TCP SYN scan in Nmap tool based on  Local IP range of user devices.
Basically,In Nmap tool at target position place a subnet range of user IP address for example 192.168.0.0/24(it's the range between 192.168.0.0 to the 255.255.255.0)
The Nmap tool will display the open ports of the IP addresses in between the given ranges.
We can also analyze these network packets through Wireshark.
Wireshark shows packet list and also analyzes the communication between scanner and targets.
