Acoin7 Core 0.14.2
=====================

Setup
---------------------
Acoin7 Core is the original Acoin7 client and it builds the backbone of the network. However, it downloads and stores the entire history of Acoin7 transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Acoin7 Core, visit [acoin7.org](https://acoin7.org).

Running
---------------------
The following are some helpful notes on how to run Acoin7 on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/acoin7-qt` (GUI) or
- `bin/acoin7d` (headless)

### Windows

Unpack the files into a directory, and then run acoin7-qt.exe.

### OS X

Drag Acoin7-Core to your applications folder, and then run Acoin7-Core.

### Need Help?

* See the documentation at the [Acoin7 Wiki](https://acoin7.info/)
for help and more information.
* Ask for help on [#acoin7](http://webchat.freenode.net?channels=acoin7) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=acoin7).
* Ask for help on the [Acoin7Talk](https://acoin7talk.io/) forums.

Building
---------------------
The following are developer notes on how to build Acoin7 on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Acoin7 repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/acoin7/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [Acoin7Talk](https://acoin7talk.io/) forums.
* Discuss general Acoin7 development on #acoin7-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=acoin7-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
