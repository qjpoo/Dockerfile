FROM ilegeul/debian:8-gnuarm-gcc
MAINTAINER Liviu Ionescu <ilg@livius.net>
WORKDIR /root

RUN \
apt-get -y update && \
apt-get -y upgrade && \
apt-get -y install \
libsdl1.2-dev libsdl-image1.2-dev

CMD ["/bin/bash"]

