FROM docker.elastic.co/logstash/logstash:6.6.0

# https://www.elastic.co/guide/en/logstash/current/docker-config.html

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
RUN rm -f /usr/share/logstash/config/logstash.yml

#ADD pipeline/ /usr/share/logstash/pipeline/
ADD config /usr/share/logstash/config
ADD templates /usr/share/logstash/templates