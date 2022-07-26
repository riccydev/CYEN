Cyberyen Core
=============

Setup
---------------------
Cyberyen Core is the original Cyberyen client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Cyberyen transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Cyberyen Core, visit [litecoin.org](https://litecoin.org/).

Running
---------------------
The following are some helpful notes on how to run Cyberyen Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/litecoin-qt` (GUI) or
- `bin/litecoind` (headless)

### Windows

Unpack the files into a directory, and then run litecoin-qt.exe.

### macOS

Drag Cyberyen Core to your applications folder, and then run Cyberyen Core.

### Need Help?

* See the documentation at the [Cyberyen Wiki](https://litecoin.info/) for help and more information.
* Ask for help on [#litecoin](https://webchat.freenode.net/#litecoin) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#litecoin).
* Ask for help on the [CyberyenTalk](https://litecointalk.io/) forums, in the [Technical Support board](https://litecointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Cyberyen Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Cyberyen repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [CyberyenTalk](https://litecointalk.io/) forums.
* Discuss general Cyberyen development on #litecoin-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#litecoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
