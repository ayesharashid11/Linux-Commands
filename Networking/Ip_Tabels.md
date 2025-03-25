
```sudo apt install iptables```
```sudo iptables -l```


```iptables -A INPUT -p tcp -s <ip_address> --dport 22 -j Accept```
A -> Add rule
-p -> protocol
-s -> source
-d -> destination
-dport -> destination port
-j -> action to take

```iptables -A INPUT -p tcp  --dport 22 -j DROP```
this will help user to connect from anywhere not from a perticular ip

![image](https://github.com/user-attachments/assets/728b30a5-4d68-4224-bb13-3868519be69e)

```iptables -D OUTPUT 5```
delete a output rule from position 5
