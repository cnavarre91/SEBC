1-Start Hive:
#curl -X POST -u cnavarre91:cloudera 'http://localhost:7180/api/v1/clusters/SEBC/services/hive/commands/start'

2-Stop Hive:
#curl -X POST -u cnavarre91:cloudera 'http://localhost:7180/api/v1/clusters/SEBC/services/hive/commands/stop'

3-Check the status:
#curl -u cnavarre91:cloudera   'http://localhost:7180/api/v1/clusters/SEBC/services'


