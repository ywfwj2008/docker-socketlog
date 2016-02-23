# docker-socketlog
This Dockerfile builds an image with the [socketlog](https://github.com/luofei614/SocketLog). Based on node image.

Quick Start
-----------

This image uses ENTRYPOINT to run the containers as an executable.

Starting a SocketLog Server instance is simple:

    docker run -d -p 1116:1116 -p 1229:1229 ywfwj2008/socketlog


or run it with daemons:

    docker run -d -p 1116:1116 -p 1229:1229 ywfwj2008/socketlog > /dev/null &