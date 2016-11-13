FROM     resin/rpi-raspbian:jessie

RUN apt-get update && \
    cp /usr/share/zoneinfo/Europe/Kiev /etc/localtime && \
    echo "Europe/Kiev" > /etc/timezone && \
    dpkg-reconfigure --frontend noninteractive tzdata
