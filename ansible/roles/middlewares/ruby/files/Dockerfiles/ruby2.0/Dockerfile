FROM ruby:2.0.0
MAINTAINER Ryuichi Tanaka <mapserver2007@gmail.com>
RUN mkdir /root/ansible
RUN mkdir /root/secret_keys
WORKDIR /root/ansible

RUN yum -y install sudo
RUN yum -y install gcc
RUN yum -y install git
RUN yum -y install python-devel
RUN yum -y install python-setuptools
RUN yum -y install epel-release
RUN yum -y install python-pip
RUN pip install ansible
