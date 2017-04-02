```
Cloud provider-> AWS
Nodes ->
      ec2-34-252-142-89.eu-west-1.compute.amazonaws.com -> 34.252.142.89 (192.168.0.56)
      ec2-34-251-191-150.eu-west-1.compute.amazonaws.com -> 34.251.191.150 (192.168.0.209)
      ec2-34-252-31-160.eu-west-1.compute.amazonaws.com -> 34.252.31.160 (192.168.0.75)
      ec2-34-248-216-73.eu-west-1.compute.amazonaws.com -> 34.248.216.73 (192.168.0.125)
      ec2-34-252-142-49.eu-west-1.compute.amazonaws.com -> 34.252.142.49 (192.168.0.127)
Linux release (cat /etc/*-release) ->
      NAME="Red Hat Enterprise Linux Server"
      VERSION="7.3 (Maipo)"
      ID="rhel"
      ID_LIKE="fedora"
      VERSION_ID="7.3"
      PRETTY_NAME="Red Hat Enterprise Linux Server 7.3 (Maipo)"
      ANSI_COLOR="0;31"
      CPE_NAME="cpe:/o:redhat:enterprise_linux:7.3:GA:server"
      HOME_URL="https://www.redhat.com/"
      BUG_REPORT_URL="https://bugzilla.redhat.com/"

Disk capacity on each node (df -h) ->
   1-ec2-34-252-142-89.eu-west-1.compute.amazonaws.com -> 34.252.142.89 (192.168.0.56):
        Filesystem      Size  Used Avail Use% Mounted on
        /dev/xvda2       65G  1.2G   64G   2% /
   2-ec2-34-251-191-150.eu-west-1.compute.amazonaws.com -> 34.251.191.150 (192.168.0.209):
        Filesystem      Size  Used Avail Use% Mounted on
        /dev/xvda2       65G  1.2G   64G   2% /
   3-ec2-34-252-31-160.eu-west-1.compute.amazonaws.com -> 34.252.31.160 (192.168.0.75)
        Filesystem      Size  Used Avail Use% Mounted on
        /dev/xvda2       65G  1.2G   64G   2% /
   4- ec2-34-248-216-73.eu-west-1.compute.amazonaws.com -> 34.248.216.73 (192.168.0.125)
        Filesystem      Size  Used Avail Use% Mounted on
        /dev/xvda2       65G  1.2G   64G   2% /
   5-ec2-34-252-142-49.eu-west-1.compute.amazonaws.com -> 34.252.142.49 (192.168.0.127)
        Filesystem      Size  Used Avail Use% Mounted on
        /dev/xvda2       65G  1.2G   64G   2% /
        
 Command yum repolist enabled ->
[root@ip-192-168-0-56 ~]# yum repolist enabled
Loaded plugins: amazon-id, rhui-lb, search-disabled-repos
repo id                                                              repo name                                                                          status
!rhui-REGION-client-config-server-7/x86_64                           Red Hat Update Infrastructure 2.0 Client Configuration Server 7                         6
!rhui-REGION-rhel-server-releases/7Server/x86_64                     Red Hat Enterprise Linux Server 7 (RPMs)                                           14,038
!rhui-REGION-rhel-server-rh-common/7Server/x86_64                    Red Hat Enterprise Linux Server 7 RH Common (RPMs)                                    209
repolist: 14,253


Adding users (useradd -u UID user) ->
    Ex. neymar -> useradd -u 2010 neymar 
Create group-> Ex. barca -> groupadd barca
Adding users to the group-> usermod -aG barca ronaldo
Listing /etc/passwd->
          [root@ip-192-168-0-56 ~]# egrep 'neymar|ronaldo' /etc/passwd
          neymar:x:2010:2010::/home/neymar:/bin/bash
          ronaldo:x:2016:2016::/home/ronaldo:/bin/bash
Listing /etc/group ->
           [root@ip-192-168-0-56 ~]# egrep 'barca|merengues' /etc/group
           barca:x:2011:ronaldo
           merengues:x:2013:neymar

```
