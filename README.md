# elastic-stack
Config files I use for Elastic Stack

# db2-mvs-jdbc-logstash.conf

Initial file config works for logstash-6.2.3 on Red Hat Enterprise Linux Server
------------------------------------------------
Assuming logstash is installed:
Test Config:
 <logstash_install_directory>bin/logstash -t -f <path_to_config>/db2-mvs-jdbc-logstash.conf
Run Config:
 <logstash_install_directory>bin/logstash -f <path_to_config>/db2-mvs-jdbc-logstash.conf
