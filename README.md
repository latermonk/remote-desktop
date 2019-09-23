# remote-desktop    

##   CentOS7 安装远程桌面      
https://www.cnblogs.com/jhxxb/p/10987058.html    



##  Ubuntu VNC     
sharing config share    

https://www.techrepublic.com/article/how-to-enable-remote-desktop-connections-in-ubuntu-18-04/     


vnc连接时报错： 不符合安全设置  

```
gsettings set org.gnome.Vino require-encryption false    
```
即可



##  Ubuntu xrdp     

Issues with xRDP and Ubuntu 18.04.2 – How to fix it     

https://c-nergy.be/blog/?p=13390   

```

apt-get install xserver-xorg-core    

apt-get -y install xserver-xorg-input-all    

apt-get install xrdp

```   






