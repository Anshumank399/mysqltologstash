# mysql to elasticsearch
Convert Database Mysql to Elasticsearch using Logsatash with JDBC plugin.

Steps:
1.	Install and Run Elasticsearch.
2.	Run Logstash using the command (bin\logstash –f logstash.config) by creating the .conf (configure) file in the syntax using JDBC.         Example in this repository given. Place the .conf file in the logstash folder directly. 
3.	Check for the index document added using the request (http://localhost:9200/_cat/indices?v) and contents of elasticsearch files in         Json format at request (http://localhost:9200/nameofindex/_search?pretty=true)


      *Make sure while running the logstash with .conf file, Mysql Database is up and running along with Elasticsearch.*
