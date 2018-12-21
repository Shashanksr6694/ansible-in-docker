# ansible-in-docker

Ansible inside Docker for consistent running of ansible inside your host on docker for DevOps environment

Building 

$docker build  --build-arg BUILD_DATE=`date -u +”%Y-%m-%dT%H:%M:%SZ”` -t ansible-in-docker:latest .

Tagging


Running

$ docker run --rm -it shashanksr/ansible-in-docker /bin/sh
