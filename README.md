# ElasticstackWithFileBeatsDockersetup

Elasticsearch, logstash, kibana and a seporate filebeats setup. 

Make sure elk-stack is running before starting filebeats. It will then read and parse the example logs files to logstash, which will forward it to elasticsearch. 

Create index via kibana for received data. 
