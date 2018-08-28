FROM ubuntu:14.04

RUN apt-get update && \
    apt-get install gcc make openjdk-7-jdk-headless python python-pip \
        build-essential debhelper autotools-dev autoconf automake libtool git \
        lsb-release devscripts equivs apt-transport-https -y && \
    pip install boto3 && curl -sSL https://rvm.io/mpapis.asc | gpg --import - && curl -sSL https://get.rvm.io | bash -s stable --ruby