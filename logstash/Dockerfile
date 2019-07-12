#FROM docker.elastic.co/logstash/logstash:6.2.2
FROM docker.elastic.co/logstash/logstash:7.2.0

LABEL maintainer="genius840215@163.com"

COPY ./config /usr/share/logstash/config

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER logstash
