FROM ubuntu:18.04

RUN apt-get update \
  && apt-get install --no-install-recommends --yes --force-yes \
    locales \
    curl \
    dnsutils \
    httpie \
    iputils-ping \
    mysql-client \
    net-tools \
    telnet \
    vim \
    nano \
    wget \
    openssh-client
CMD ["tail", "-f", "/var/log/dpkg.log"]
