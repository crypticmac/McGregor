Mcgregor Core 0.10.4
=====================

Setup
---------------------
[Mcgregor Core] is the original Mcgregor client and it builds the backbone of the network. However, it downloads and stores the entire history of Mcgregor transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once. If you would like the process to go faster you can [download the blockchain directly](bootstrap.md).

Running
---------------------
The following are some helpful notes on how to run Mcgregor on your native platform.

### Unix

You need the Qt4 run-time libraries to run Mcgregor-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/Mcgregor-qt (GUI, 32-bit) or bin/32/Mcgregord (headless, 32-bit)
- bin/64/Mcgregor-qt (GUI, 64-bit) or bin/64/Mcgregord (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run Mcgregor-qt.exe.

### OS X

Drag Mcgregor-Qt to your applications folder, and then run Mcgregor-Qt.

### Need Help?



Building
---------------------
The following are developer notes on how to build Mcgregor on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)

Development
---------------------
The Mcgregor repo's [root README](https://github.com/crypticmac/McGregor/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Coding Guidelines](coding.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)

- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)

### Resources


### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
