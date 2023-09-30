# Sample Dockerfile
FROM wiremock/wiremock:latest as build

COPY wiremock /home/wiremock

ENTRYPOINT ["/docker-entrypoint.sh", "--global-response-templating", "--disable-gzip", "--verbose"]