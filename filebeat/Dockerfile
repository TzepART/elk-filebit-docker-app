FROM docker.elastic.co/beats/filebeat:6.6.0

# https://www.elastic.co/guide/en/beats/filebeat/6.6/running-on-docker.html

COPY filebeat.yml /usr/share/filebeat/filebeat.yml
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
USER filebeat