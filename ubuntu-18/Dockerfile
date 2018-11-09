FROM ubuntu:18.04

RUN apt-get update && apt-get install gcc make openjdk-8-jdk-headless python python-pip build-essential debhelper autotools-dev autoconf automake libtool git lsb-release devscripts equivs sudo ruby-curb ruby-dev -y && \
    pip install boto3
RUN adduser --disabled-password --gecos "" nginx && usermod -aG sudo nginx
