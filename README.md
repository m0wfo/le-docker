le-docker
=========

Logentries/Docker integration examples

rsyslog
===

Usage:

From the root of the repository:

    $ docker build -i -t le/example .
    $ docker run -i -t le/example /bin/bash

And to log some data:

    $ rsyslog
    $ logger 'hello, world!'
