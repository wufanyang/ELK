FROM docker.elastic.co/logstash/logstash:6.1.2

USER root
COPY ./mysql-connector-java-5.1.45-bin.jar /usr/share

RUN bin/logstash-plugin install logstash-input-jdbc
