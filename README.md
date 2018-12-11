# DockerNginxLog

- A Dockerized application is deployed to serve a static website via Nginx

- fluentd is used to ship Nginx request logs to ElasticSearch

- A standalone solution is provided that includes both webapp and EFK stack using docker-compose.

## Building

### Docker

    $ docker-compose up --build

- Navigate to http://localhost:8080 to view the HTML5 website.
- Navigate to http://localhost:5601 to view HTTP requests in a Kibana dashboard.