# IP Finder

Bash script that will check the IPs addresses not pinging from a nmap -sn scan on CIDR range.
When there is no IP management it is better then nothing.
A normal scan with show up hosts . This shows which IPs are not being used. 
The idea is to eventually run this over multiple subnets and write to a file the open IP addresses every 10 minutes or so 
The file will be accessable by all members of the team via NFS so they only have to click a file on their Desktop
