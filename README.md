# mysql56ipv6
Docker-compose for mysql56 with ipv6 support

How to:
To build up run
`docker-compose up -d`

To get your ipv6 address.
Windows:
ssh docker@<docker-machine-ip-address>
password: tcuser

### Windows 
In terminal:
$ docker-machine.exe ip
192.168.99.100



ip addr
find interface whitch uses your docker machine ip address
e.g.: 
 eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP group default qlen 1000
    link/ether 08:00:27:f4:d6:c5 brd ff:ff:ff:ff:ff:ff
    inet 192.168.99.100/24 brd 192.168.99.255 scope global eth1
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fef4:d6c5/64 scope link
       valid_lft forever preferred_lft forever
	   
	   
=> your ipv6 ip address `fe80::a00:27ff:fef4:d6c5`


### Linux:
todo