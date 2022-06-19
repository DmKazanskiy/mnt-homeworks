FROM pycontribs/centos:7
ENV LANG en_US.UTF-8
RUN yum update -y && yum install -y java-1.8.0-openjdk-devel python3 python3-pip sudo && yum clean all
RUN pip3 install -U pip
RUN pip3 install ansible
