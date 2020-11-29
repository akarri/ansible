# ansible
Provision 4 containers using docker-compose and start practicing the ansible playbooks.

Installation steps are provided in Notes file.


Push the docker container to remote docker hub


syntax:
docker commit <running container id>  <dockerhub repository id>/<imagename:tag>

Example:
docker commit 3a4dd10c465b 1073100xkarani/centos-ssh:7

Good github links
https://github.com/linuxserver
