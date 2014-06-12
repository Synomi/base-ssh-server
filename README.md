base-ssh-server
===============

A base Ubuntu 14.04 container with openssh-server installed.

# ssh password

    password

# starting container

    docker run -d -p 8022:22 garland/base-ssh-server

# After container starts
You can then ssh into it

    ssh root@<IP_OF_CONTAINER> -p 8022
