Command output (ls /etc/yum.repos.d)
      [root@ip-192-168-0-56 /]# ls /etc/yum.repos.d
      cloudera-manager.repo  redhat.repo  redhat-rhui-client-config.repo  redhat-rhui.repo  rhui-load-balancers.conf
Command for scm_prepare_database.sh ->
     sudo /usr/share/cmf/schema/scm_prepare_database.sh mysql -h ip-192-168-0-56.eu-west-1.compute.internal -uroot -pcloudera --scm-host localhost scm scm scm
