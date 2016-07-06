
ExclusiveCoin is a PoS-based cryptocurrency.

ExclusiveCoin uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01p,
			  Berkeley DB 4.8,
			  QT5 to compile


Block Spacing: 60 Seconds
Stake Minimum Age: 24 Hours

Port: 23230
RPC Port: 23231


BUILD LINUX
-----------
1) git clone https://github.com/exclusivecoin/ExclusiveCoin

2) cd ExclusiveCoin/src

3) sudo make -f makefile.unix            # Headless

(optional)

4) strip exclusivecoind

5) sudo cp exclusivecoind /usr/local/bin
