FROM logstash:6.6.1

RUN bin/logstash-plugin install logstash-input-jdbc

COPY ./ojdbc6.jar /opt/ojdbc6.jar

COPY ./logstash.yml /usr/share/logstash/config/logstash.yml

COPY ./logstash.conf /usr/share/logstash/pipeline/logstash.conf