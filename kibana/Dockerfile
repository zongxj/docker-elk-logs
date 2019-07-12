#FROM docker.elastic.co/kibana/kibana:6.2.2
FROM docker.elastic.co/kibana/kibana:7.2.0

LABEL maintainer="zongxj_cn@foxmail.com"

COPY ./config/kibana.yml /usr/share/kibana/config/kibana.yml

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER kibana
