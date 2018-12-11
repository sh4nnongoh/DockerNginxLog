# DockerNginxLog

● Deploy a Dockerized application serving a static website via (e.g. via Nginx) that displays
a custom welcome page (but not the default page for the web server used)

● Use fluentd to ship Nginx request logs to an output of your choice (e.g. S3,
ElasticSearch)

● Provide a standalone solution including both webapp and fluentd using docker-compose
and/or a kubernetes deployment (plain manifest or helm chart)
