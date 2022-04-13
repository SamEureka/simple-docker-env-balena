FROM balenalib/%%BALENA_MACHINE_NAME%%-debian:stretch

COPY docker /usr/bin/docker

WORKDIR /usr/src/app

COPY start.sh .
RUN chmod +x start.sh

CMD [ "./start.sh" ]

