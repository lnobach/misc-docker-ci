FROM coturn/coturn:4.12.0-alpine

USER root:root

RUN apk add --no-cache \
        sudo

COPY entrypoint /entrypoint

ENTRYPOINT /entrypoint
