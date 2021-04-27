From centos

RUN yum -y install openssh-server

RUN useradd remote_user && \
    echo "1234" | passwrd remote_user --stdin && \
    mkdir /home/remote_user/.ssh && \
    chmod 700 /home/remote_user/.ssh