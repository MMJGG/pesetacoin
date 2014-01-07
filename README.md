# PesetaCoin [PTC, P]
http://pesetacoin.info/

![PesetaCoin](http://i44.tinypic.com/6j3w5w.png)

## What is PesetaCoin?  
Pesetacoin is like Bitcoin, but based on Litecoin (Scrypt Algorithm).
Visit us at: http://pesetacoin.com/ for more info

## License
PesetaCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How much PesetaCoin will exist?
Total of 166,386,000 PTC will be minted in 4 Years

### How do I get PesetaCoins?
Solo Mining, pooled mining or using exchanges


### How to compile pesetacoind

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC 	16638

P2P 	16639

TESTNET	16640
