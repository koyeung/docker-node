docker-node
===========

Run [Node.js](https://nodejs.org) on [Alpine Linux](http://www.alpinelinux.org)/[armhf](https://hub.docker.com/r/armhf/alpine/) docker image.

reference:
- Dockerfiles from [node](https://hub.docker.com/_/node/)
- [alpinelinux/aports/blob/master/main/nodejs/APKBUILD](https://github.com/alpinelinux/aports/blob/master/main/nodejs/APKBUILD)


Setup docker image
====================

Method 1: Building
------------------

    # docker build --rm -t <username>/armhf-node:5.8.0 .

Method 2: Pull from Docker Hub
------------------------------

    # docker pull docker.io/<username>armhf-node:5.8.0
