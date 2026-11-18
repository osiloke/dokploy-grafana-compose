FROM curlimages/curl:8.10.1 AS curl
FROM grafana/loki:3.7.10
COPY --from=curl /usr/local/bin/curl /usr/local/bin/curl
COPY loki.yml /etc/loki/config.yml
