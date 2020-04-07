
-----  DESCRIPTION  -----

these binaries are for raspberry pi 4 with the processor armv7l.
The files were tested on the operation system NOOBS 3.3.1 based on Debian Buster.

-----  DOWNLOAD  -----

download the package with typing in a terminal:

wget https://github.com/allforonebusiness/allforonebusiness/releases/allforonebusiness_4.1.2.1_NOOBSBuster_QT.zip

-----  REQUIRED DEPENDENCES  -----

You will requirethe following dependencies:

libssl1.1,libboost-all-dev,libevent-2,libgmp-dev

Please install with:

sudo apt install libssl1.1 libboost-all-dev libevent-2 libgmp-dev

-----  INSTALLATION   -----

To install the file just type the command in a terminal:


unzip allforonebusiness_4.1.2.1_NOOBSBuster_QT.zip

cd AFO_Noobs/

sudo cp allforonebusiness* /usr/local/bin/

sudo cp test_allforonebusiness* /usr/local/bin/

launch the wallet by typing:

allforonebusiness-qt&

-----  REFERENCE  ------

Written by Davide Lustro

e-mail buddandroid@gmail.com