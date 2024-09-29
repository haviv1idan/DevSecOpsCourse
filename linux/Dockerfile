FROM ubuntu:22.04

USER root

RUN apt update && apt upgrade -y

RUN apt install net-tools network-manager iputils-ping ssh telnet openssh-server vim -y

CMD ["bash"]
