FROM coturn/coturn:4.16.0-alpine

USER root:root

RUN apk add --no-cache \
        sudo

COPY entrypoint /entrypoint

ENTRYPOINT /entrypoint
