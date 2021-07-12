Educoin Core Staging Repository (Version 1.0.0)
===========================


What is Educoin Core?
-------------

Educoin is an experimental digital currency that enables instant, private
payments to anyone, anywhere in the world. Educoin uses peer-to-peer technology
to operate with no central authority: managing transactions and issuing money
are carried out collectively by the network.

Users hold the crypto keys to their own money and transact directly with each other, 
with the help of a P2P network to check for double-spending. Educoin Core is the 
name of the open source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Educoin Core software, see https://educoins.io


Educoin Specification
-------------

- Coin Name: Educoin (Ticker: CED)
- Algorithm: X11 (PoW & Masternode)
- Block Size: 3 MB (~1,440 Blocks/Day)
- Block Rewards: 200 CED/Block (PoW: 50%, Masternode: 50%)
- Pre-Mined: ~19.23% (Total 50,000,000 CED)
- Max Supply: 260,000,000 CED


Setup & Running
---------------------
Educoin Core is the original Educoin client and it builds the backbone of the network.
However, it downloads and stores the entire history of Educoin transactions;
depending on the speed of your computer and network connection, the synchronization
process can take anywhere from a few hours to a day or more.

The following are some helpful notes on how to run Educoin on your native platform.

### Unix

Unpack the files into a directory and run Educoin-qt (GUI, 64-bit) or Educoind (headless, 64-bit).

### Windows

Unpack the files into a directory, and then run Educoin-qt.exe (GUI, 32/64-bit).

### OSX

Drag Educoin-qt to your applications folder, and then run Educoin-qt (GUI) or Educoind (headless).

### Configuration ./educoin/educoin.conf

rpcuser=rpc_educoin</br>
rpcpassword=eAerhMZQtJF5LdR2oBQ3K1Zqeq9J2WxaJzY</br>
rpcbind=0.0.0.0</br>
rpcallowip=127.0.0.1</br>
port=38110</br>
rpcport=38109</br>
listen=1</br>
server=1</br>
txindex=1</br>
daemon=1</br>
addnode=node1.educoins.io</br>
addnode=node2.educoins.io


License
-------

Educoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
