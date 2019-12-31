FROM scratch
ADD centos-7-x86_64-docker.tar.xz /

LABEL org.label-schema.schema-version="1.0" \
    org.label-schema.name="CentOS Base Image" \
    org.label-schema.vendor="CentOS" \
    org.label-schema.license="GPLv2" \
    org.label-schema.build-date="20191001"

RUN yum -y install awk \
    yum -y install which \
    yum -y install sed \
    yum -y install bzip2 \
    yum clean all \
    
CMD ["/bin/bash"]