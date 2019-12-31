FROM shoyooyo/centos7:ver3

WORKDIR "/opt/"
ADD management-server-1.6.0-103.x86_64.rpm /opt/management-server-1.6.0-103.x86_64.rpm
RUN rpm -ivh /opt/management-server-1.6.0-103.x86_64.rpm
RUN rm -rf /opt/management-server-1.6.0-103.x86_64.rpm

CMD ["/usr/sbin/init"]