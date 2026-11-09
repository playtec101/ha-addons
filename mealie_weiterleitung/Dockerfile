ARG BUILD_FROM=alpine:3.20
FROM alpine:3.20
RUN apk add --no-cache socat
CMD ["socat", "TCP-LISTEN:9381,fork,reuseaddr", "TCP:192.168.178.8:9381"]
