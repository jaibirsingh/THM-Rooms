* Every computer has a total of 65535 available ports; however, many of these are registered as standard ports.
* For example, a HTTP Webservice can nearly always be found on port 80 of the server. A HTTPS Webservice can be found on port 443. Windows NETBIOS can be found on port 139 and SMB can be found on port 445.
*  only port numbers 0 to 1023 are reserved for privileged services and designated as well-known ports.
*  What switch would you use to save the nmap results in three major formats at once?
  * -oA

* How would you tell nmap to scan all ports?
  * -p-
 
*  Configure a firewall to respond with a RST TCP packet. For example, in IPtables for Linux, a simple version of the command would be as follows:

* `iptables -I INPUT -p tcp --dport <port> -j REJECT --reject-with tcp-reset`

* This can make it extremely difficult (if not impossible) to get an accurate reading of the target(s).
