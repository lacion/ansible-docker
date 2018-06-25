Docker
======

[![Build Status](https://travis-ci.org/lacion/ansible-docker.svg?branch=master)](https://travis-ci.org/lacion/ansible-docker)

Simple Ansible Role to install Docker CE Edition.

Role Variables
--------------
Set `docker_install_compose` to `True` to install docker-compose alongside docker, you can spesify compose version using `docker_compose_version`

you can also use diferent release channels for docker by using `docker_apt_release_channel`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lacion.ansible-docker

License
-------

MIT