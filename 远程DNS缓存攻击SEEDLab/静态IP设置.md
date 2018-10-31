## Ubuntu虚拟机静态IP设置
- sudo nano /etc/network/interfaces <br/>iface eth0 inet static<br/>address IP<br/>netmask 255.255.255.0<br/>gateway 192.168.1.1
- sudo nano /etc/resolv.conf 添加以下设置<br/>nameserver 192.168.1.1
- 重启网络 /etc/init.d/networking restart