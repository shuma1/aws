
2- AN INSTACE ON CLI        
shumail@shumail-Inspiron-N5110:~/Downloads$ ssh -i "shuma.pem" ec2-user@13.232.131.142
The authenticity of host '13.232.131.142 (13.232.131.142)' can't be established.
ECDSA key fingerprint is SHA256:73jP98lF1+xWVZvZEA//nMwhxJPEl9nacG/O2LamTDI.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added '13.232.131.142' (ECDSA) to the list of known hosts.

       __|  __|_  )
       _|  (     /   Amazon Linux AMI
      ___|\___|___|

https://aws.amazon.com/amazon-linux-ami/2018.03-release-notes/
11 package(s) needed for security, out of 13 available
Run "sudo yum update" to apply all updates.
[ec2-user@ip-172-17-1-181 ~]$ ls -a
.  ..  .bash_logout  .bash_profile  .bashrc  .ssh
[ec2-user@ip-172-17-1-181 ~]$ ping www.google.com
PING www.google.com (172.217.27.196) 56(84) bytes of data.
64 bytes from bom07s15-in-f4.1e100.net (172.217.27.196): icmp_seq=1 ttl=53 time=1.16 ms
64 bytes from bom07s15-in-f4.1e100.net (172.217.27.196): icmp_seq=2 ttl=53 time=1.26 ms
64 bytes from bom07s15-in-f4.1e100.net (172.217.27.196): icmp_seq=3 ttl=53 time=1.23 ms
64 bytes from bom07s15-in-f4.1e100.net (172.217.27.196): icmp_seq=4 ttl=53 time=1.23 ms
64 bytes from bom07s15-in-f4.1e100.net (172.217.27.196): icmp_seq=5 ttl=53 time=1.27 ms
64 bytes from bom07s15-in-f4.1e100.net (172.217.27.196): icmp_seq=6 ttl=53 time=1.31 ms
^C
--- www.google.com ping statistics ---
6 packets transmitted, 6 received, 0% packet loss, time 5009ms
rtt min/avg/max/mdev = 1.169/1.249/1.313/0.044 ms


