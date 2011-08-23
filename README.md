node-haiku
==========

Bindings for an evented language (Node.js) to an evented OS (Haiku, née OpenBeOS).

I'm gauging interest right now, so please become a watcher if you're interested.  It's currently very early in development.  Contributions are very welcome (see Contributing).

Have experience with:

* Node.js internals?
* The Haiku API?
* Porting languages to Haiku?
* Anything else related?

Your input, interest, and contributions are valuable and encouraged!

Introduction
------------

While reading through the [Haiku documentation][hdocs] (more specifically, [Programming the Be Operating System][pbeos]), I realized that the event loop structure of the Haiku API is very similar to what [Node.js][njs] provides.  Writing bindings for Node to interact with Haiku seems interesting.  Primarily, this is a place for me to play with both Node and Haiku as I would like to learn more about both, just for fun.

Want more of a background?  See the documentation on the message (event) loop, BLooper, BHandler and BMessage.

  [hdocs]: http://haiku-os.org/documents
  [pbeos]: http://haiku-os.org/legacy-docs/programming_the_be_operating_system.pdf
  [njs]: http://nodejs.org/

To Dos
------

* Get Node.js to build on Haiku (an obvious prereq. :) ).  See https://github.com/benjaminoakes/node
* Make a simple wrapper to allow a "hello world" GUI program to be made

Contributing
------------

Wow, you want to contribute?  That's great, thanks!  Please contact @benjaminoakes with any pull requests.  Any and all contributions are welcome.

Getting Started:

* [Download][hdl] the lasest release of Haiku
* You'll probably want to run it virtualized.  [VirtualBox][vboxdl] is a good option.
* Clone the repository (git's included with Haiku)
  
In a terminal:

    git clone git://github.com/benjaminoakes/node-haiku.git

  [hdl]: http://haiku-os.org/get-haiku
  [vboxdl]: http://www.virtualbox.org/wiki/Downloads
  [njsdl]: http://nodejs.org/dist/node-v0.4.7.tar.gz
