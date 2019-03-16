FROM alpine:latest

RUN apk add --update wget nfs-utils &&\
    rm -rf /var/cache/apk/*

ENTRYPOINT ["/usr/bin/ros", "entrypoint"]
