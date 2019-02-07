# docker-recipes :thought_balloon: :rocket:

Varied projects bootstrapped in [Docker][docker-url] environments!

[docker-url]: https://docs.docker.com/engine

## Distributed Computing
1. :globe_with_meridians: [Mesos][mesos-url] - Container Orchestration of an ElasticSearch cluster, using Mesos
1. :zap: [Spark][spark-url] - Run distributed in-memory processing using PySpark
1. :elephant: [Hadoop2][hadoop-url] - Configure and provision a multi-node hadoop cluster
1. :ship: [K8s][k8s-url] - Configuring a single-node K8s cluster

[mesos-url]: https://github.com/jakebrinkmann/docker-mesos-marathon
[spark-url]: https://github.com/jakebrinkmann/docker-spark
[hadoop-url]: https://github.com/jakebrinkmann/docker-hadoop
[k8s-url]: https://github.com/jakebrinkmann/docker-etcd-k8s

## Microservices
1. :cloud: [Gunicorn][gunicorn-url] - Host a multi-tenant Python-Flask web application hosted behind an nginx proxy

[gunicorn-url]: https://github.com/jakebrinkmann/docker-nginx-flask

## Message Queues
1. :rabbit2: [RabbitMQ][rabbitmq-url] - Keep a full queue of work-orders as broadcast messages using rabbitmq
1. :mailbox: [ActiveMQ][activemq-url] - Track objects pushed into a ceph-cluster (s3) using an ActiveMQ message-oriented-middleware
1. :coffee: [Kafka][kafka-url] - Keep a full queue of work-orders as broadcast messages using kafka

[activemq-url]: https://github.com/jakebrinkmann/docker-activemq
[rabbitmq-url]: https://github.com/jakebrinkmann/docker-rabbitmq
[kafka-url]: https://github.com/jakebrinkmann/docker-kafka

## Databases & Storage
1. :earth_africa: [PostGIS][postgis-url] - Query point datasets using straight GeoJSON
1. :arrow_up_down: [Ceph][ceph-url] - Configure S3-compatible object storage buckets

[postgis-url]: https://github.com/jakebrinkmann/docker-postgis
[ceph-url]: https://github.com/jakebrinkmann/docker-ceph

## Visualizations
1. :snake: [Dash/Bokeh][flask-dataviz-url] - Quickly create interactive plots in python
1. :chart_with_downwards_trend: [d3.js][d3-url] - Easily create custom visualizations with interactive SVG elements

[flask-dataviz-url]: https://github.com/jakebrinkmann/docker-flask-dataviz
[d3-url]: https://github.com/jakebrinkmann/docker-node-d3

## Dashboards
1. :chart_with_upwards_trend: [Grafana][grafana-url] - Query a PostgreSQL DB and create interactive charts easily using Grafana simple-json backend
1. :bar_chart: [Logstash/ElasticSearch/Kibana][elk-url] - Split remote logs into key/value pairs, and generate interactive plots

[grafana-url]: https://github.com/jakebrinkmann/docker-grafana
[elk-url]: https://github.com/jakebrinkmann/docker-elk

## Automation
1. :necktie: [Jenkins][jenkins-url] - Create complex multi-machine continuous delivery pipelines using Jenkins

[jenkins-url]: https://github.com/jakebrinkmann/docker-jenkins
