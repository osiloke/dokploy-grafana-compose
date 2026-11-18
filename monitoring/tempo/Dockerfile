FROM curlimages/curl:8.10.1 AS curl
FROM grafana/tempo:3.1.1
COPY --from=curl /usr/local/bin/curl /usr/local/bin/curl
COPY tempo.yml /etc/tempo/config.yml
