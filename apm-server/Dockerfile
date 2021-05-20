ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/apm/apm-server:${ELK_VERSION}

COPY --chown=apm-server:apm-server ./config/apm-server.yml /usr/share/apm-server/apm-server.yml
