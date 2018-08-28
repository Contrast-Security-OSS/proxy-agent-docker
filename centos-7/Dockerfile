FROM centos:7

RUN yum install -y gcc make rpm-build java-1.8.0-openjdk-devel epel-release && \
    yum install -y python-pip git yum-utils sudo which libcurl libcurl-devel curl && \
    pip install boto3 && curl -sSL https://rvm.io/mpapis.asc | gpg --import - && curl -sSL https://get.rvm.io | bash -s stable --ruby