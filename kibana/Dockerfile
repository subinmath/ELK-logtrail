FROM docker.elastic.co/kibana/kibana-oss:6.1.3
RUN cd /opt/kibana
RUN kibana-plugin install https://github.com/sivasamyk/logtrail/releases/download/v0.1.25/logtrail-6.1.3-0.1.25.zip
EXPOSE 5601