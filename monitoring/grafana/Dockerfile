FROM curlimages/curl:8.10.1 AS curl
FROM grafana/grafana:13.2.6
COPY --from=curl /usr/local/bin/curl /usr/local/bin/curl
COPY datasources.yml /etc/grafana/provisioning/datasources/datasources.yml
