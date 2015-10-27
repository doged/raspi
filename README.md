![raspi-doged](https://raw.githubusercontent.com/doged/raspi/master/doged-raspi.png)

#raspberry pi files for doged wallet/daemon

sudo apt-get install build-essential libqrencode-dev libevent-dev pkg-config libtool autotools-dev autoconf automake libssl-dev libboost-all-dev libminiupnpc-dev libdb++-dev qt4-qmake libqt4-dev libboost-all-dev libssl-dev git

after installing dependencies:

to compile daemon:

cd src && make -f makefile.unix

to compile qt gui wallet:

qmake

make

makestrip --strip-unneeded dogecoindark-qt

visit our irc chat!

[![Visit our IRC Chat!](https://kiwiirc.com/buttons/irc.freenode.net/dogecoindark.png)](https://kiwiirc.com/client/irc.freenode.net/?nick=doged|?&theme=cli#dogecoindark)
