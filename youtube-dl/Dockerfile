FROM alpine:3.10
LABEL MAINTAINER="Eric Kreunen <kreunen.eric@gmail.com>"

RUN set -ex; \
    apk add --no-cache ca-certificates \
                       ffmpeg \
                       youtube-dl

WORKDIR /data

ENTRYPOINT ["youtube-dl"]
CMD ["--help"]
