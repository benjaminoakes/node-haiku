node-haiku
==========

Node.js bindings for Haiku (née OpenBeOS), an event-based OS.

Currently very early in development, contributions welcome (see Contributing).

Introduction
------------

While reading through the [Haiku documentation][hdocs] (more specifically, [Programming the Be Operating System][pbeos]), I realized that the event loop structure of the Haiku API is very similar to what [Node.js][nodejs] provides.  Writing bindings for Node to interact with Haiku seems interesting.  Primarily, this is a place for me to play with both Node and Haiku as I would like to learn more about both, just for fun.

  [hdocs]: http://haiku-os.org/documents
  [pbeos]: http://haiku-os.org/legacy-docs/programming_the_be_operating_system.pdf
  [njs]: http://nodejs.org/

To Dos
------

* Make a simple wrapper to allow a "hello world" GUI program to be made

Contributing
------------

Wow, you want to contribute?  That's great, thanks!  Please contact @benjaminoakes with any pull requests.  Any and all contributions are welcome.

Getting Started:

* [Download][hdl] the lasest release of Haiku
* You'll probably want to run it virtualized.  [VirtualBox][vboxdl] is a good option.
* Download and build [Node.js v0.4.7][njsdl] (the current target)

In a terminal:

    wget http://nodejs.org/dist/node-v0.4.7.tar.gz
    tar xvfz node-v0.4.7.tar.gz
    cd node-v0.4.7
    ./configure
    make
    make install

* Clone the repository (git's included with Haiku)
  
In a terminal:

    git clone git://github.com/benjaminoakes/node-haiku.git)

  [hdl]: http://haiku-os.org/get-haiku
  [vboxdl]: http://www.virtualbox.org/wiki/Downloads
  [njsdl]: http://nodejs.org/dist/node-v0.4.7.tar.gz
