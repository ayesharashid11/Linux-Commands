# ssh 
used to connect to remote server

```ssh <ip address>``` 

create a ssh ```ssh <name_of_host_server>```

-> key pair= private key + pblic key

Password-Less ssh:
ssh -keygen -t rsa

Public keypath: /home/<user>/.ssh/id_rsa.pub
Private key: /home/<user>/.ssh/id_rsa
-> copy public key to remote server
```ssh-copy-id <user>@<remote_server_ip>```
# scp
copy data over ssh

```scp -pr home/<user>/media/ <remote_ip>:/home/<user>```

to check the port connectd ssh -> ```sudo netstat -ntlp | grep ssh```



