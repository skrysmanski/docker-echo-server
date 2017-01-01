Docker echo server
==================
A small tcp echo server written in Golang, packaged in a Docker container.

You may run it like this (in foreground):

	$ docker run --rm -ti -p 8800:8800 krys/echo-server

or (in background):

	$ docker run --rm -d -p 8800:8800 krys/echo-server

Credits
-------
All credits go to:

	https://github.com/luisbebop/echo-server
