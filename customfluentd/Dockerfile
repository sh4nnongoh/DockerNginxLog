FROM fluent/fluentd:v0.12-debian
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.5"]
RUN rm /fluentd/etc/fluent.conf
COPY ./conf/fluent.conf /fluentd/etc