FROM alpine:3.18.3
RUN apk add rsync bash screen && mkdir -p /mnt/source && mkdir /mnt/destination
COPY rsyncd.conf /etc/rsyncd.conf
CMD tail -f /dev/null