# These are two docker compose for using ELK(elasticsearch Logstash Kibana) single node and cluster.

I used Rabbitmq for input of my logstash.

**Please sure that you need at least 262144 for max_map_count:**

```sysctl -w vm.max_map_count=262144```

You can read **Elasticsearch data stream.pdf** for getting extra information about everything that is used in these docker compose files.
