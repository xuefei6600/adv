# adv
docker of adv

# Dockerfile
FROM centos:7.4.1708
ADD step.sh /usr/bin
ADD pre_formatter.py /usr/bin
