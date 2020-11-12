通过cat /proc/net/dev获取当前linux网卡信息

1.第一个流量监控脚本适用于centos
# traffic_monitor.sh
network eth0 traffic monitor   for centos
执行效果
复制代码代码如下:

# sh traffic.sh eth0

2.第二个流量监控脚本

#traffic.sh
执行代码
#./traffic.sh eth0

[root@localhost hbshell]# ./traffic.sh 
IN: 1.74 KB
OUT:1.17 KB
