# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.4.0

COPY ./postgresql-42.1.1.jar /
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-jdbc
