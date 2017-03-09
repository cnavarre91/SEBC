1-Autenticate user:
  kinit superhdfs@CLOUDERA_KERBEROS

2-Klist ouput result:

[root@ip-172-31-16-117 ~]# klist
Ticket cache: KEYRING:persistent:0:krb_ccache_NhUIZRw
Default principal: superhdfs@CLOUDERA_KERBEROS

Valid starting       Expires              Service principal
03/09/2017 10:12:48  03/10/2017 10:12:48  krbtgt/CLOUDERA_KERBEROS@CLOUDERA_KERBEROS
        renew until 03/16/2017 11:12:48
