FROM ubuntu:latest
RUN \ 
    apt-get update -y \
    && apt-get install -y curl nano wget libgd2-dev net-tools supervisor dnsutils \
    && curl -sL https://deb.nodesource.com/setup_8.x | bash \
    && apt-get install --yes nodejs \
    && apt-get install --yes build-essential \
    && curl -o- -L https://yarnpkg.com/install.sh | bash

