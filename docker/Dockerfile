FROM ubuntu:24.04

RUN useradd -ms /bin/bash ansible
COPY id_rsa.pub /home/ansible/.ssh/authorized_keys

RUN apt update && apt install -y openssh-server sudo net-tools

RUN echo "ansible ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers

EXPOSE 22

ENTRYPOINT service ssh restart && sleep infinity
