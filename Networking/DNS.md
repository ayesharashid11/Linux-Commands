1. To find the IP address of DNS server
   ```cat /etc/resolv.conf ``` -> nameserver  contains the IP address
   
3. Which file is responsible for host file-based DNS resolution?
   /etc/host
   
3.What is the configuration file used for the DNS Server?
/etc/resolv.conf

5. change the DNS Server to google's DNS which is 8.8.8.8
  sudo vi /etc/resolv.conf
namesever <ip>

6. Change the order to DNS first and then hosts.
   Update  vi /etc/nsswitch.conf and change the line to hosts:   dns files
   
