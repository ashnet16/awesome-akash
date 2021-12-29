# Standalone Splunk deployment image for deployment on Akash v1.
# Not production ready.

FROM centos:centos7 
MAINTAINER misunderstood.ashley (aishili.mitchell@gmail.com)
RUN yum -y update; yum clean all
RUN yum -y install sudo epel-release; yum clean all
FROM splunk/splunk:latest
