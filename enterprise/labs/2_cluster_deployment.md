Command: 
 # curl -X GET -u "cnavarre91:cloudera" -i http://ip-172-31-16-117.eu-west-1.compute.internal:7180/api/v2/cm/deployment
Date: Wed, 08 Mar 2017 10:49:10 GMT
Transfer-Encoding: chunked
Server: Jetty(6.1.26.cloudera.4)

{
  "timestamp" : "2017-03-08T10:49:10.352Z",
  "clusters" : [ {
    "name" : "SEBC",
    "version" : "CDH5",
    "services" : [ {
      "name" : "zookeeper",
      "type" : "ZOOKEEPER",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "SERVER",
          "items" : [ {
            "name" : "maxSessionTimeout",
            "value" : "60000"
          }, {
            "name" : "zookeeper_server_java_heapsize",
            "value" : "268435456"
          } ]
        } ],
        "items" : [ ]
      },
      "roles" : [ {
        "name" : "zookeeper-SERVER-00cbe0bc2737a97239a0527341afc71b",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "163rf8neloexfbksx88gs2t24"
          }, {
            "name" : "serverId",
            "value" : "2"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "ebuj3e4i3rpp7bg1x44r1pnlz"
          }, {
            "name" : "serverId",
            "value" : "3"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "eptqd57tvrw5akaqn7o7uor0b"
          }, {
            "name" : "serverId",
            "value" : "1"
          } ]
        }
      } ],
      "displayName" : "ZooKeeper"
    }, {
      "name" : "hdfs",
      "type" : "HDFS",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "DATANODE",
          "items" : [ {
            "name" : "datanode_java_heapsize",
            "value" : "1073741824"
          }, {
            "name" : "dfs_data_dir_list",
            "value" : "/dfs/dn"
          }, {
            "name" : "dfs_datanode_data_dir_perm",
            "value" : "755"
          }, {
            "name" : "dfs_datanode_du_reserved",
            "value" : "6441190604"
          }, {
            "name" : "dfs_datanode_max_locked_memory",
            "value" : "4294967296"
          }, {
            "name" : "rm_cpu_shares",
            "value" : "2000"
          }, {
            "name" : "rm_io_weight",
            "value" : "1000"
          } ]
        }, {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "dfs_client_use_trash",
            "value" : "true"
          } ]
        }, {
          "roleType" : "JOURNALNODE",
          "items" : [ {
            "name" : "dfs_journalnode_edits_dir",
            "value" : "/dfs/jn"
          } ]
        }, {
          "roleType" : "NAMENODE",
          "items" : [ {
            "name" : "dfs_name_dir_list",
            "value" : "/dfs/nn"
          }, {
            "name" : "dfs_namenode_servicerpc_address",
            "value" : "8022"
          } ]
        }, {
          "roleType" : "SECONDARYNAMENODE",
          "items" : [ {
            "name" : "fs_checkpoint_dir_list",
            "value" : "/dfs/snn"
          } ]
        } ],
        "items" : [ {
          "name" : "dfs_ha_fencing_cloudera_manager_secret_key",
          "value" : "GTdko4qDlhLYVoxsZJJFE8bqoD5LXv"
        }, {
          "name" : "dfs_ha_fencing_methods",
          "value" : "shell(true)"
        }, {
          "name" : "fc_authorization_secret_key",
          "value" : "LHTQu5HtaGGknObhm6mUA8CTrNLZle"
        }, {
          "name" : "hdfs_under_replicated_blocks_thresholds",
          "value" : "{\"warning\":10,\"critical\":50}"
        }, {
          "name" : "http_auth_signature_secret",
          "value" : "vxDfi7MwgtH96yM8AphD8RrWqs9lmF"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "10"
        }, {
          "name" : "service_health_suppression_hdfs_canary_health",
          "value" : "true"
        }, {
          "name" : "service_health_suppression_hdfs_under_replicated_blocks",
          "value" : "true"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hdfs-DATANODE-00cbe0bc2737a97239a0527341afc71b",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "5u4dr8h4mp26beqrdazbgo7jr"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "f4zojtp3metzkbxv5sapahrhw"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-493e51ee52e52b8a20b550ae062c0009",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "cf755262-fc8b-4bd6-a175-07dee7ea6c8e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "11uy3qjq82rjh8jduk99tau9n"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "7bu5soju4p4dt0dfxm5jvh36g"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-00cbe0bc2737a97239a0527341afc71b",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "ev3pr2xs5bas8zrj9qjv05hrl"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "ebvgd32i5th6wlbg9sqt2lwte"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-00cbe0bc2737a97239a0527341afc71b",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "6tjee603vmhkuqlhr4qccq2bx"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "7bt4fhtkono4tkiaeysc8d68m"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "9pslduhw6qfniedmyn8neslqx"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-00cbe0bc2737a97239a0527341afc71b",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover_enabled",
            "value" : "true"
          }, {
            "name" : "dfs_federation_namenode_nameservice",
            "value" : "HAHDFS"
          }, {
            "name" : "dfs_namenode_quorum_journal_name",
            "value" : "HAHDFS"
          }, {
            "name" : "namenode_id",
            "value" : "101"
          }, {
            "name" : "role_jceks_password",
            "value" : "b978u5ulx0owccb8z15q44xzr"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover_enabled",
            "value" : "true"
          }, {
            "name" : "dfs_federation_namenode_nameservice",
            "value" : "HAHDFS"
          }, {
            "name" : "dfs_namenode_quorum_journal_name",
            "value" : "HAHDFS"
          }, {
            "name" : "namenode_id",
            "value" : "33"
          }, {
            "name" : "role_jceks_password",
            "value" : "4qt4iflxhjfgbdn4z98j0dpyt"
          } ]
        }
      } ],
      "displayName" : "HDFS"
    }, {
      "name" : "solr",
      "type" : "SOLR",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "SOLR_SERVER",
          "items" : [ {
            "name" : "rm_cpu_shares",
            "value" : "20"
          }, {
            "name" : "rm_io_weight",
            "value" : "100"
          }, {
            "name" : "role_health_suppression_solr_server_scm_health",
            "value" : "true"
          }, {
            "name" : "solr_java_direct_memory_size",
            "value" : "1073741824"
          }, {
            "name" : "solr_java_heapsize",
            "value" : "1073741824"
          } ]
        } ],
        "items" : [ {
          "name" : "hdfs_service",
          "value" : "hdfs"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "0"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "solr-GATEWAY-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "solr-SOLR_SERVER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "SOLR_SERVER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "631nos85flqgejsetfhzbw3xp"
          } ]
        }
      } ],
      "displayName" : "Solr"
    }, {
      "name" : "yarn",
      "type" : "YARN",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "mapred_reduce_tasks",
            "value" : "3"
          }, {
            "name" : "mapred_submit_replication",
            "value" : "1"
          } ]
        }, {
          "roleType" : "JOBHISTORY",
          "items" : [ {
            "name" : "mr2_jobhistory_java_heapsize",
            "value" : "268435456"
          } ]
        }, {
          "roleType" : "NODEMANAGER",
          "items" : [ {
            "name" : "node_manager_java_heapsize",
            "value" : "268435456"
          }, {
            "name" : "rm_cpu_shares",
            "value" : "1800"
          }, {
            "name" : "rm_io_weight",
            "value" : "900"
          }, {
            "name" : "yarn_nodemanager_heartbeat_interval_ms",
            "value" : "100"
          }, {
            "name" : "yarn_nodemanager_local_dirs",
            "value" : "/yarn/nm"
          }, {
            "name" : "yarn_nodemanager_log_dirs",
            "value" : "/yarn/container-logs"
          }, {
            "name" : "yarn_nodemanager_resource_cpu_vcores",
            "value" : "3"
          }, {
            "name" : "yarn_nodemanager_resource_memory_mb",
            "value" : "1024"
          } ]
        }, {
          "roleType" : "RESOURCEMANAGER",
          "items" : [ {
            "name" : "resource_manager_java_heapsize",
            "value" : "268435456"
          }, {
            "name" : "yarn_scheduler_maximum_allocation_mb",
            "value" : "3597"
          }, {
            "name" : "yarn_scheduler_maximum_allocation_vcores",
            "value" : "3"
          } ]
        } ],
        "items" : [ {
          "name" : "hdfs_service",
          "value" : "hdfs"
        }, {
          "name" : "rm_dirty",
          "value" : "false"
        }, {
          "name" : "rm_last_allocation_percentage",
          "value" : "90"
        }, {
          "name" : "yarn_service_cgroups",
          "value" : "false"
        }, {
          "name" : "yarn_service_lce_always",
          "value" : "false"
        }, {
          "name" : "zk_authorization_secret_key",
          "value" : "klVT4g4UhPJn4fJLcqFr5RlLoZllNL"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "yarn-GATEWAY-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "yarn-JOBHISTORY-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "JOBHISTORY",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "y9g12afz3k1qh35q759d3amv"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "dbmht4qto9l53na1e8zv9g00g"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "awoqps2y5s95rbdf0uk7zh934"
          } ]
        }
      }, {
        "name" : "yarn-RESOURCEMANAGER-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "RESOURCEMANAGER",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ {
            "name" : "rm_id",
            "value" : "113"
          }, {
            "name" : "role_jceks_password",
            "value" : "4v4ci3felhx6lp8c0zv927g6i"
          } ]
        }
      }, {
        "name" : "yarn-RESOURCEMANAGER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "RESOURCEMANAGER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "rm_id",
            "value" : "54"
          }, {
            "name" : "role_jceks_password",
            "value" : "xutcnqvbi31gdzltirzdl0v5"
          } ]
        }
      } ],
      "displayName" : "YARN (MR2 Included)"
    }, {
      "name" : "spark_on_yarn",
      "type" : "SPARK_ON_YARN",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "SPARK_YARN_HISTORY_SERVER",
          "items" : [ {
            "name" : "history_server_max_heapsize",
            "value" : "349175808"
          } ]
        } ],
        "items" : [ {
          "name" : "yarn_service",
          "value" : "yarn"
        } ]
      },
      "roles" : [ {
        "name" : "spar40365358-SPARK_YARN_HISTORY_SERVER-8c9dcfb912b6545c273c09852",
        "type" : "SPARK_YARN_HISTORY_SERVER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "7zgvzxxw8c1ubnhykka2cbj2y"
          } ]
        }
      }, {
        "name" : "spark_on_yarn-GATEWAY-00cbe0bc2737a97239a0527341afc71b",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "spark_on_yarn-GATEWAY-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "spark_on_yarn-GATEWAY-493e51ee52e52b8a20b550ae062c0009",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "cf755262-fc8b-4bd6-a175-07dee7ea6c8e"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "spark_on_yarn-GATEWAY-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ ]
        }
      } ],
      "displayName" : "Spark"
    }, {
      "name" : "hive",
      "type" : "HIVE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "HIVEMETASTORE",
          "items" : [ {
            "name" : "hive_metastore_java_heapsize",
            "value" : "268435456"
          }, {
            "name" : "role_health_suppression_hivemetastore_canary_health",
            "value" : "true"
          } ]
        }, {
          "roleType" : "HIVESERVER2",
          "items" : [ {
            "name" : "hiveserver2_java_heapsize",
            "value" : "268435456"
          }, {
            "name" : "hiveserver2_spark_driver_memory",
            "value" : "966367641"
          }, {
            "name" : "hiveserver2_spark_executor_cores",
            "value" : "4"
          }, {
            "name" : "hiveserver2_spark_executor_memory",
            "value" : "912680550"
          }, {
            "name" : "hiveserver2_spark_yarn_driver_memory_overhead",
            "value" : "102"
          }, {
            "name" : "hiveserver2_spark_yarn_executor_memory_overhead",
            "value" : "153"
          } ]
        } ],
        "items" : [ {
          "name" : "hbase_service",
          "value" : "none"
        }, {
          "name" : "hive_metastore_database_host",
          "value" : "ip-172-31-16-117.eu-west-1.compute.internal"
        }, {
          "name" : "hive_metastore_database_name",
          "value" : "hive"
        }, {
          "name" : "hive_metastore_database_password",
          "value" : "mq5PYMmtPJ"
        }, {
          "name" : "hive_metastore_database_port",
          "value" : "7432"
        }, {
          "name" : "hive_metastore_database_type",
          "value" : "postgresql"
        }, {
          "name" : "mapreduce_yarn_service",
          "value" : "yarn"
        }, {
          "name" : "spark_on_yarn_service",
          "value" : "spark_on_yarn"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hive-GATEWAY-00cbe0bc2737a97239a0527341afc71b",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-239566ac17aeb97c4163834ce7f1c12a",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-HIVEMETASTORE-00cbe0bc2737a97239a0527341afc71b",
        "type" : "HIVEMETASTORE",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "uszcfik6zsxyeuuepgwn6fdn"
          } ]
        }
      }, {
        "name" : "hive-HIVEMETASTORE-493e51ee52e52b8a20b550ae062c0009",
        "type" : "HIVEMETASTORE",
        "hostRef" : {
          "hostId" : "cf755262-fc8b-4bd6-a175-07dee7ea6c8e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "1l9ocms0era4vy9rxpvehequb"
          } ]
        }
      }, {
        "name" : "hive-HIVEMETASTORE-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "HIVEMETASTORE",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "c4180nfm67wbjv0y2hj05aihb"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-00cbe0bc2737a97239a0527341afc71b",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "6dtwxha896qiei6khbd0yypc7"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-493e51ee52e52b8a20b550ae062c0009",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "cf755262-fc8b-4bd6-a175-07dee7ea6c8e"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "cwem4xzjue9pmnilnimty9exc"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "f2d5u4cd3mwfwxv78cn56e8k"
          } ]
        }
      }, {
        "name" : "hive-WEBHCAT-00cbe0bc2737a97239a0527341afc71b",
        "type" : "WEBHCAT",
        "hostRef" : {
          "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6"
        },
        "config" : {
          "items" : [ {
            "name" : "hive_webhcat_secret_key",
            "value" : "JKm00CieLtdfhX2RTPZWCKrVk5o0tg"
          }, {
            "name" : "role_jceks_password",
            "value" : "dc8eiqx2ek1sqs87ucpj3wtxj"
          } ]
        }
      }, {
        "name" : "hive-WEBHCAT-493e51ee52e52b8a20b550ae062c0009",
        "type" : "WEBHCAT",
        "hostRef" : {
          "hostId" : "cf755262-fc8b-4bd6-a175-07dee7ea6c8e"
        },
        "config" : {
          "items" : [ {
            "name" : "hive_webhcat_secret_key",
            "value" : "PE0fFLpew3TBT5KoxZynZU8zRI74Lo"
          }, {
            "name" : "role_jceks_password",
            "value" : "e0n6nbmfmhi19455b9dqni4gu"
          } ]
        }
      } ],
      "displayName" : "Hive"
    }, {
      "name" : "oozie",
      "type" : "OOZIE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "OOZIE_SERVER",
          "items" : [ {
            "name" : "oozie_database_host",
            "value" : "ip-172-31-16-117.eu-west-1.compute.internal:7432"
          }, {
            "name" : "oozie_database_name",
            "value" : "oozie_oozie_server"
          }, {
            "name" : "oozie_database_password",
            "value" : "vcQKaumAT7"
          }, {
            "name" : "oozie_database_type",
            "value" : "postgresql"
          }, {
            "name" : "oozie_database_user",
            "value" : "oozie_oozie_server"
          }, {
            "name" : "oozie_java_heapsize",
            "value" : "268435456"
          } ]
        } ],
        "items" : [ {
          "name" : "hive_service",
          "value" : "hive"
        }, {
          "name" : "mapreduce_yarn_service",
          "value" : "yarn"
        }, {
          "name" : "spark_on_yarn_service",
          "value" : "spark_on_yarn"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "oozie-OOZIE_SERVER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "OOZIE_SERVER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "al6ds0y88mqtdasoezpfvwzd4"
          } ]
        }
      } ],
      "displayName" : "Oozie"
    }, {
      "name" : "hue",
      "type" : "HUE",
      "config" : {
        "roleTypeConfigs" : [ ],
        "items" : [ {
          "name" : "database_host",
          "value" : "ip-172-31-16-117.eu-west-1.compute.internal"
        }, {
          "name" : "database_password",
          "value" : "x3JEeNXFIv"
        }, {
          "name" : "database_port",
          "value" : "7432"
        }, {
          "name" : "database_type",
          "value" : "postgresql"
        }, {
          "name" : "hbase_service",
          "value" : "none"
        }, {
          "name" : "hive_service",
          "value" : "hive"
        }, {
          "name" : "hue_service_safety_valve",
          "value" : "[desktop]\nallowed_hosts=*\n"
        }, {
          "name" : "hue_webhdfs",
          "value" : "hdfs-NAMENODE-8c9dcfb912b6545c273c0985246f7cb8"
        }, {
          "name" : "impala_service",
          "value" : "none"
        }, {
          "name" : "oozie_service",
          "value" : "oozie"
        }, {
          "name" : "service_config_suppression_hue_hbase_thrift_server_validator",
          "value" : "true"
        }, {
          "name" : "solr_service",
          "value" : "solr"
        }, {
          "name" : "zookeeper_service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hue-HUE_SERVER-8c9dcfb912b6545c273c0985246f7cb8",
        "type" : "HUE_SERVER",
        "hostRef" : {
          "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
        },
        "config" : {
          "items" : [ {
            "name" : "role_jceks_password",
            "value" : "5n8isp4mvh0pve01g6hoh1gff"
          }, {
            "name" : "secret_key",
            "value" : "zSCdLkhC2dy4IXTBPucjrc8EyqhkHm"
          } ]
        }
      } ],
      "displayName" : "Hue"
    } ]
  } ],
  "hosts" : [ {
    "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6",
    "ipAddress" : "172.31.17.107",
    "hostname" : "ip-172-31-17-107.eu-west-1.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ {
        "name" : "memory_overcommit_threshold",
        "value" : "0.5"
      } ]
    }
  }, {
    "hostId" : "03b48a93-320e-4cf5-8ff8-168e2c9a6cc6",
    "ipAddress" : "172.31.18.217",
    "hostname" : "ip-172-31-18-217.eu-west-1.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "a27d8403-cf18-43da-84b1-be035c6df93e",
    "ipAddress" : "172.31.24.133",
    "hostname" : "ip-172-31-24-133.eu-west-1.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "cf755262-fc8b-4bd6-a175-07dee7ea6c8e",
    "ipAddress" : "172.31.24.31",
    "hostname" : "ip-172-31-24-31.eu-west-1.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  } ],
  "users" : [ {
    "name" : "__cloudera_internal_user__mgmt-EVENTSERVER-8c9dcfb912b6545c273c0985246f7cb8",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "989575c32274fdce1e88f1642271aa17e6e8d683f299faea34e48ee930e8f040",
    "pwSalt" : -7223923518901035792,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-HOSTMONITOR-8c9dcfb912b6545c273c0985246f7cb8",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "d6d6536f178e47c293dd859921b8d1fad27d11408d0ae1f079a0f391e4b68da8",
    "pwSalt" : -5813178635018935165,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-REPORTSMANAGER-8c9dcfb912b6545c273c0985246f7cb8",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "9e0f5a2d2bcd0c7b8f0cbb041eb44a52c9603070ed55abc022cd5cf7278bdbbd",
    "pwSalt" : 2076093853838782040,
    "pwLogin" : true
  }, {
    "name" : "__cloudera_internal_user__mgmt-SERVICEMONITOR-8c9dcfb912b6545c273c0985246f7cb8",
    "roles" : [ "ROLE_USER" ],
    "pwHash" : "fcf5e20171ae0002a1280508be42ab2c997b53e1ab51deca477857a9df3ff9fc",
    "pwSalt" : -3967711718124207083,
    "pwLogin" : true
  }, {
    "name" : "admin",
    "roles" : [ "ROLE_LIMITED" ],
    "pwHash" : "aee8e47a711f793f4ddd1651b89a392e9ad4da571f372bdd1fb00507bde75288",
    "pwSalt" : 5960440107925263367,
    "pwLogin" : true
  }, {
    "name" : "cnavarre91",
    "roles" : [ "ROLE_ADMIN" ],
    "pwHash" : "a2b7553a6aea888fd46d68e8b7480bea5784ded65c56b3342af0e448576aa913",
    "pwSalt" : -8433593400145836802,
    "pwLogin" : true
  }, {
    "name" : "minotaur",
    "roles" : [ "ROLE_CONFIGURATOR" ],
    "pwHash" : "05c9dde6babfc74526315ce208947eaac96de65c78d47514ced0598fb05c037a",
    "pwSalt" : 6363066805016845825,
    "pwLogin" : true
  } ],
  "versionInfo" : {
    "version" : "5.10.0",
    "buildUser" : "jenkins",
    "buildTimestamp" : "20170120-1037",
    "gitHash" : "aa0b5cd5eceaefe2f971c13ab657020d96bb842a",
    "snapshot" : false
  },
  "managementService" : {
    "name" : "mgmt",
    "type" : "MGMT",
    "config" : {
      "roleTypeConfigs" : [ {
        "roleType" : "EVENTSERVER",
        "items" : [ {
          "name" : "event_server_heapsize",
          "value" : "268435456"
        } ]
      }, {
        "roleType" : "REPORTSMANAGER",
        "items" : [ {
          "name" : "headlamp_database_host",
          "value" : "ip-172-31-16-117.eu-west-1.compute.internal:7432"
        }, {
          "name" : "headlamp_database_name",
          "value" : "rman"
        }, {
          "name" : "headlamp_database_password",
          "value" : "GvbA5WBE0h"
        }, {
          "name" : "headlamp_database_type",
          "value" : "postgresql"
        }, {
          "name" : "headlamp_database_user",
          "value" : "rman"
        }, {
          "name" : "headlamp_heapsize",
          "value" : "268435456"
        } ]
      } ],
      "items" : [ ]
    },
    "roles" : [ {
      "name" : "mgmt-ALERTPUBLISHER-8c9dcfb912b6545c273c0985246f7cb8",
      "type" : "ALERTPUBLISHER",
      "hostRef" : {
        "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "82cx6kktqycq82gngfz8wul1w"
        } ]
      }
    }, {
      "name" : "mgmt-EVENTSERVER-8c9dcfb912b6545c273c0985246f7cb8",
      "type" : "EVENTSERVER",
      "hostRef" : {
        "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "dklkgkcmnkbiv0f46z0bwh82n"
        } ]
      }
    }, {
      "name" : "mgmt-HOSTMONITOR-8c9dcfb912b6545c273c0985246f7cb8",
      "type" : "HOSTMONITOR",
      "hostRef" : {
        "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "bocq8urx6r4mancmanrpe5apj"
        } ]
      }
    }, {
      "name" : "mgmt-REPORTSMANAGER-8c9dcfb912b6545c273c0985246f7cb8",
      "type" : "REPORTSMANAGER",
      "hostRef" : {
        "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "2f1substw8qfns470dzacegsb"
        } ]
      }
    }, {
      "name" : "mgmt-SERVICEMONITOR-8c9dcfb912b6545c273c0985246f7cb8",
      "type" : "SERVICEMONITOR",
      "hostRef" : {
        "hostId" : "2c1dbb12-b443-49c0-98a7-7d9af463afc6"
      },
      "config" : {
        "items" : [ {
          "name" : "role_jceks_password",
          "value" : "5luyn7k4fe9z454rmh2erdgli"
        } ]
      }
    } ],
    "displayName" : "Cloudera Management Service"
  },
  "managerSettings" : {
    "items" : [ {
      "name" : "CLUSTER_STATS_START",
      "value" : "10/21/2012 2:10"
    }, {
      "name" : "PUBLIC_CLOUD_STATUS",
      "value" : "ON_PUBLIC_CLOUD"
    }, {
      "name" : "REMOTE_PARCEL_REPO_URLS",
      "value" : "https://archive.cloudera.com/cdh5/parcels/{latest_supported}/,https://archive.cloudera.com/cdh4/parcels/latest/,https://archive.cloudera.com/impala/parcels/latest/,https://archive.cloudera.com/search/parcels/latest/,https://archive.cloudera.com/accumulo/parcels/1.4/,https://archive.cloudera.com/accumulo-c5/parcels/latest/,https://archive.cloudera.com/kafka/parcels/latest/,https://archive.cloudera.com/navigator-keytrustee5/parcels/latest/,https://archive.cloudera.com/spark/parcels/latest/,https://archive.cloudera.com/sqoop-connectors/parcels/latest/"
    } ]
  }
