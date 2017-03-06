1-Setting vw.swappiness=1
    -sysctl -w vm.swappiness=0
2-Mount attributes:
# mount
          sysfs on /sys type sysfs (rw,nosuid,nodev,noexec,relatime,seclabel)
          proc on /proc type proc (rw,nosuid,nodev,noexec,relatime)
          devtmpfs on /dev type devtmpfs (rw,nosuid,seclabel,size=7598116k,nr_inodes=18995                                                                                                             29,mode=755)
          securityfs on /sys/kernel/security type securityfs (rw,nosuid,nodev,noexec,relat                                                                                                             ime)
          tmpfs on /dev/shm type tmpfs (rw,nosuid,nodev,seclabel)
          devpts on /dev/pts type devpts (rw,nosuid,noexec,relatime,seclabel,gid=5,mode=62                                                                                                             0,ptmxmode=000)
          tmpfs on /run type tmpfs (rw,nosuid,nodev,seclabel,mode=755)
          tmpfs on /sys/fs/cgroup type tmpfs (ro,nosuid,nodev,noexec,seclabel,mode=755)
          cgroup on /sys/fs/cgroup/systemd type cgroup (rw,nosuid,nodev,noexec,relatime,xa                                                                                                             ttr,release_agent=/usr/lib/systemd/systemd-cgroups-agent,name=systemd)
          pstore on /sys/fs/pstore type pstore (rw,nosuid,nodev,noexec,relatime)
          cgroup on /sys/fs/cgroup/devices type cgroup (rw,nosuid,nodev,noexec,relatime,de                                                                                                             vices)
          cgroup on /sys/fs/cgroup/cpu,cpuacct type cgroup (rw,nosuid,nodev,noexec,relatim                                                                                                             e,cpuacct,cpu)
          cgroup on /sys/fs/cgroup/blkio type cgroup (rw,nosuid,nodev,noexec,relatime,blki                                                                                                             o)
          cgroup on /sys/fs/cgroup/perf_event type cgroup (rw,nosuid,nodev,noexec,relatime                                                                                                             ,perf_event)
          cgroup on /sys/fs/cgroup/net_cls,net_prio type cgroup (rw,nosuid,nodev,noexec,re                                                                                                             latime,net_prio,net_cls)
          cgroup on /sys/fs/cgroup/memory type cgroup (rw,nosuid,nodev,noexec,relatime,mem                                                                                                             ory)
          cgroup on /sys/fs/cgroup/cpuset type cgroup (rw,nosuid,nodev,noexec,relatime,cpu                                                                                                             set)
          cgroup on /sys/fs/cgroup/freezer type cgroup (rw,nosuid,nodev,noexec,relatime,fr                                                                                                             eezer)
          cgroup on /sys/fs/cgroup/hugetlb type cgroup (rw,nosuid,nodev,noexec,relatime,hu                                                                                                             getlb)
          cgroup on /sys/fs/cgroup/pids type cgroup (rw,nosuid,nodev,noexec,relatime,pids)
          configfs on /sys/kernel/config type configfs (rw,relatime)
          /dev/xvda2 on / type xfs (rw,relatime,seclabel,attr2,inode64,noquota)
          selinuxfs on /sys/fs/selinux type selinuxfs (rw,relatime)
          systemd-1 on /proc/sys/fs/binfmt_misc type autofs (rw,relatime,fd=29,pgrp=1,time                                                                                                             out=300,minproto=5,maxproto=5,direct)
          mqueue on /dev/mqueue type mqueue (rw,relatime,seclabel)
          hugetlbfs on /dev/hugepages type hugetlbfs (rw,relatime,seclabel)
          debugfs on /sys/kernel/debug type debugfs (rw,relatime)
          tmpfs on /run/user/1000 type tmpfs (rw,nosuid,nodev,relatime,seclabel,size=14972                                                                                                             60k,mode=700,uid=1000,gid=1000)
          [ec2-user@ip-172-31-16-117 ~]$ mount
          sysfs on /sys type sysfs (rw,nosuid,nodev,noexec,relatime,seclabel)
          proc on /proc type proc (rw,nosuid,nodev,noexec,relatime)
          devtmpfs on /dev type devtmpfs (rw,nosuid,seclabel,size=7598116k,nr_inodes=1899529,mode=755)
          securityfs on /sys/kernel/security type securityfs (rw,nosuid,nodev,noexec,relatime)
          tmpfs on /dev/shm type tmpfs (rw,nosuid,nodev,seclabel)
          devpts on /dev/pts type devpts (rw,nosuid,noexec,relatime,seclabel,gid=5,mode=620,ptmxmode=000)
          tmpfs on /run type tmpfs (rw,nosuid,nodev,seclabel,mode=755)
          tmpfs on /sys/fs/cgroup type tmpfs (ro,nosuid,nodev,noexec,seclabel,mode=755)
          cgroup on /sys/fs/cgroup/systemd type cgroup (rw,nosuid,nodev,noexec,relatime,xattr,release_agent=/usr/lib/systemd/systemd-cgroups-agent,name=systemd)
          pstore on /sys/fs/pstore type pstore (rw,nosuid,nodev,noexec,relatime)
          cgroup on /sys/fs/cgroup/devices type cgroup (rw,nosuid,nodev,noexec,relatime,devices)
          cgroup on /sys/fs/cgroup/cpu,cpuacct type cgroup (rw,nosuid,nodev,noexec,relatime,cpuacct,cpu)
          cgroup on /sys/fs/cgroup/blkio type cgroup (rw,nosuid,nodev,noexec,relatime,blkio)
          cgroup on /sys/fs/cgroup/perf_event type cgroup (rw,nosuid,nodev,noexec,relatime,perf_event)
          cgroup on /sys/fs/cgroup/net_cls,net_prio type cgroup (rw,nosuid,nodev,noexec,relatime,net_prio,net_cls)
          cgroup on /sys/fs/cgroup/memory type cgroup (rw,nosuid,nodev,noexec,relatime,memory)
          cgroup on /sys/fs/cgroup/cpuset type cgroup (rw,nosuid,nodev,noexec,relatime,cpuset)
          cgroup on /sys/fs/cgroup/freezer type cgroup (rw,nosuid,nodev,noexec,relatime,freezer)
          cgroup on /sys/fs/cgroup/hugetlb type cgroup (rw,nosuid,nodev,noexec,relatime,hugetlb)
          cgroup on /sys/fs/cgroup/pids type cgroup (rw,nosuid,nodev,noexec,relatime,pids)
          configfs on /sys/kernel/config type configfs (rw,relatime)
          /dev/xvda2 on / type xfs (rw,relatime,seclabel,attr2,inode64,noquota)
          selinuxfs on /sys/fs/selinux type selinuxfs (rw,relatime)
          systemd-1 on /proc/sys/fs/binfmt_misc type autofs (rw,relatime,fd=29,pgrp=1,timeout=300,minproto=5,maxproto=5,direct)
          mqueue on /dev/mqueue type mqueue (rw,relatime,seclabel)
          hugetlbfs on /dev/hugepages type hugetlbfs (rw,relatime,seclabel)
          debugfs on /sys/kernel/debug type debugfs (rw,relatime)
          tmpfs on /run/user/1000 type tmpfs (rw,nosuid,nodev,relatime,seclabel,size=1497260k,mode=700,uid=1000,gid=1000)

3-Reserved space for volumes
# df -h
          Filesystem      Size  Used Avail Use% Mounted on
          /dev/xvda2       60G  982M   60G   2% /
          devtmpfs        7.3G     0  7.3G   0% /dev
          tmpfs           7.2G     0  7.2G   0% /dev/shm
          tmpfs           7.2G   17M  7.2G   1% /run
          tmpfs           7.2G     0  7.2G   0% /sys/fs/cgroup
          tmpfs           1.5G     0  1.5G   0% /run/user/1000
          
4-Disabling Hugepages
        # echo never > /sys/kernel/mm/transparent_hugepage/enabled
        # echo never > /sys/kernel/mm/transparent_hugepage/defrag

          
5-The network interface:
# ifconfig
        eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 9001
                inet 172.31.16.117  netmask 255.255.240.0  broadcast 172.31.31.255
                inet6 fe80::4c0:41ff:fe51:36f1  prefixlen 64  scopeid 0x20<link>
                ether 06:c0:41:51:36:f1  txqueuelen 1000  (Ethernet)
                RX packets 2580  bytes 203828 (199.0 KiB)
                RX errors 0  dropped 0  overruns 0  frame 0
                TX packets 1897  bytes 243534 (237.8 KiB)
                TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

        lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
                inet 127.0.0.1  netmask 255.0.0.0
                inet6 ::1  prefixlen 128  scopeid 0x10<host>
                loop  txqueuelen 1  (Local Loopback)
                RX packets 4  bytes 340 (340.0 B)
                RX errors 0  dropped 0  overruns 0  frame 0
                TX packets 4  bytes 340 (340.0 B)
                TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

6-Lookup
    # nslookup 172.31.16.117
        Server:         172.31.0.2
        Address:        172.31.0.2#53

        Non-authoritative answer:
        117.16.31.172.in-addr.arpa      name = ip-172-31-16-117.eu-west-1.compute.internal.

    # nslookup 34.249.129.61.in-addr.-arpa
        Server:         172.31.0.2
        Address:        172.31.0.2#53

7-Status of nscd service
  First installing:
    #sudo yum install nscd
  Starting the service
    #systemctl start nscd.service
    
8-Status of ntpd service
  First installing:
    #sudo yum install ntp
  Starting the service
    #systemctl start ntpd




