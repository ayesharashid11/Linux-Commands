# Linux kernel
it communicates between computer hardeware and its process. (resoures)

# Tasks
1. Memory management
2 Process Management
3.device trackers
4. system calls and security

```uname -r```
command to check kernel version
for e.g -> 4.15..0-72-generic
4 -> kernel version 
15 -> major version
7 -> minor version
72 -> patch release

# Hardware
 USB -> comuter -> kernel space/ device driver -> user space -> udev -> /dev/(device name)

 ```dmsg | grep -i usb```
 ```udevadm monitor``` -> tell details of device
 ```lspci``` -> lists all PCI devices of the system. e.g etherneths, video cards, graphic card,  raid controllers

 ```lsblk``` -> lists all blocked devices in system
 ```lscpu``` -> list number of cores, models, threads.

 ```lsmem --summary``` -> list memory size of the system.

 ```free -m ``` -> total memrory used in system
 ```lshw``` -> detail hardware info.

