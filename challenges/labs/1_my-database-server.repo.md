Using the repository ->
[root@ip-192-168-0-56 /]# sudo yum repolist
Loaded plugins: amazon-id, rhui-lb, search-disabled-repos
repo id                                                   repo name                                                                status
rhui-REGION-client-config-server-7/x86_64                 Red Hat Update Infrastructure 2.0 Client Configuration Server 7               6
rhui-REGION-rhel-server-releases/7Server/x86_64           Red Hat Enterprise Linux Server 7 (RPMs)                                 14,038
rhui-REGION-rhel-server-rh-common/7Server/x86_64          Red Hat Enterprise Linux Server 7 RH Common (RPMs)                          209
repolist: 14,253

Hostname Master server (34.252.142.89) -> ip-192-168-0-56.eu-west-1.compute.internal 

MySql Version ->
    [root@ip-192-168-0-56 /]# mysql -V
    mysql  Ver 15.1 Distrib 5.5.52-MariaDB, for Linux (x86_64) using readline 5.1

Show databases ->
                MariaDB [(none)]> show databases;
                +--------------------+
                | Database           |
                +--------------------+
                | information_schema |
                | hive               |
                | hue                |
                | mysql              |
                | oozie              |
                | performance_schema |
                | rman               |
                | scm                |
                | sentry             |
                +--------------------+
                
   
