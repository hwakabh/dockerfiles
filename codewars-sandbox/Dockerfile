FROM centos:7
LABEL MAINTAINER="hwakabh"

WORKDIR /tmp

RUN set -x && \
    yum -y install git && \
    yum -y install https://centos7.iuscommunity.org/ius-release.rpm && \
    yum -y install python34u python34u-libs python34u-devel python34-pip && \
    curl -sL https://rpm.nodesource.com/setup_13.x | sudo bash - && \
    yum -y install gcc-c++ make nodejs
