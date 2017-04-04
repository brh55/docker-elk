# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.2.2

# Add your logstash plugins setup here
RUN logstash -e input { http { port => 9601 } } output { stdout { codec => rubydebug} }
