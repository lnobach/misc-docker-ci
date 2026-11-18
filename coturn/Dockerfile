FROM coturn/coturn:4.19.1-alpine

USER root:root

RUN apk add --no-cache \
        sudo

COPY entrypoint /entrypoint

ENTRYPOINT /entrypoint
