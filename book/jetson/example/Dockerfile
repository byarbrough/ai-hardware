# Example to add a package and change the default command
# Build with `docker build -t alpine-pubip .`
# Run with `docker run --rm alpine-pubip` to display host public IP address
# Run with `docker run --rm -it alpine-pubip /bin/sh` to launch shell
FROM alpine:3

RUN apk add curl

CMD ["/usr/bin/curl", "-s", "ifconfig.me"]
