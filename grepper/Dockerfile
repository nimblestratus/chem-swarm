FROM voxxit/alpine-rpi
MAINTAINER Matt Williams <matt@matthewkwilliams.com>
ADD grepper /
RUN apk --update add findutils grep \
    && chmod +x /grepper
VOLUME /data
ENTRYPOINT /grepper 
