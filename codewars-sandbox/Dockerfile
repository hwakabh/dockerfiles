FROM centos:7
LABEL MAINTAINER="hwakabh"

WORKDIR /tmp

RUN set -x && \
    yum -y install https://centos7.iuscommunity.org/ius-release.rpm && \
    yum -y install python34u python34u-libs python34u-devel python34-pip && \
    yum -y install nodejs
