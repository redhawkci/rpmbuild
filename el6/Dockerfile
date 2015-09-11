FROM centos:6

RUN yum update -y && \
    yum install -y epel-release && \
    yum install -y @buildsys-build \
                   rpmdevtools \
                   yum-utils && \
    yum clean all

RUN rpmdev-setuptree
