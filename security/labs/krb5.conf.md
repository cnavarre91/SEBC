# Configuration snippets may be placed in this directory as well
includedir /etc/krb5.conf.d/

[logging]
 default = FILE:/var/log/krb5libs.log
 kdc = FILE:/var/log/krb5kdc.log
 admin_server = FILE:/var/log/kadmind.log

[libdefaults]
 dns_lookup_realm = false
 ticket_lifetime = 24h
 renew_lifetime = 7d
 forwardable = true
 rdns = false
 default_realm = CLOUDERA_KERBEROS
 default_ccache_name = KEYRING:persistent:%{uid}
 dns_lookup_kdc = false

[realms]
 CLOUDERA_KERBEROS = {
  kdc = ip-172-31-16-117.eu-west-1.compute.internal
  admin_server = ip-172-31-16-117.eu-west-1.compute.internal
 }

[domain_realm]
 .example.com = CLOUDERA_KERBEROS
 example.com = CLOUDERA_KERBEROS
