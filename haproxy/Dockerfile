FROM haproxy:latest
USER root
RUN apt update && apt install -y curl
USER haproxy
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg