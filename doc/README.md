BitcoinMeta Core
=============

Setup
---------------------
BitcoinMeta Core is the original BitcoinMeta client and it builds the backbone of the network. It downloads and, by default, stores the entire history of BitcoinMeta transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download BitcoinMeta Core, visit [bitcoinmeta.org](https://bitcoinmeta.org/).

Running
---------------------
The following are some helpful notes on how to run BitcoinMeta Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/bitcoinmeta-qt` (GUI) or
- `bin/bitcoinmetad` (headless)

### Windows

Unpack the files into a directory, and then run bitcoinmeta-qt.exe.

### macOS

Drag BitcoinMeta Core to your applications folder, and then run BitcoinMeta Core.

### Need Help?

* See the documentation at the [BitcoinMeta Wiki](https://bitcoinmeta.info/)
for help and more information.
* Ask for help on [#bitcoinmeta](http://webchat.freenode.net?channels=bitcoinmeta) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=bitcoinmeta).
* Ask for help on the [BitcoinMetaTalk](https://bitcoinmetatalk.io/) forums, in the [Technical Support section](https://bitcoinmetatalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build BitcoinMeta Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

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
The BitcoinMeta repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [BitcoinMetaTalk](https://bitcoinmetatalk.io/) forums.
* Discuss general BitcoinMeta development on #bitcoinmeta-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=bitcoinmeta-dev.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
