# NetM [NTM]
NetM is an open source peer-to-peer cryptocurrency and network, oriented to corporate use.


## (What is NetM?)
NetM is a network like Bitcoin, Litecoin or others that is oriented to the market of payments and electronic transactions for a B2B market.
Basically NetM offers a payment network with a electronic currency for intercommunicate other transactional networks as complementary infrastructure to the current organizational infrastructure .
https://www.netmred.com

## License (License)
NetM is released under the terms of the MIT license. See (COPYING)
for more information or see http://opensource.org/licenses/MIT.


##Asked Questions (FAQ)

### Release of NetM
Each block will generate 10,000 coins to miners per block with PoW.

### Currency 
(NTM) is own built-in currency of the NetM network, public released it provide liquidity and exchange between digital assets, a way of save value in the network.

### (How to mine) 
Scrypt Proof of Work

60 seconds Blocks

4 hours Diff Readjustment

Per block 10,000 NTM Reward 

### (How to build `netmd`)
bash

sudo apt-get install build-essential \
                     libssl-dev \
                     libdb5.1++-dev \
                     libboost-all-dev \
                     libqrencode-dev \
                     libminiupnpc-dev

cd src/
make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1
strip netmd

./netmd


### Ports (Ports)
RPC port 22557
Listen port 22558

