FROM coturn/coturn:4.17.2-alpine

USER root:root

RUN apk add --no-cache \
        sudo

COPY entrypoint /entrypoint

ENTRYPOINT /entrypoint
