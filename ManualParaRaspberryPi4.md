-----  DESCRIPTÓN  -----

Estos programas son para el raspberri pi 5, con el procesador armv71.
Yo hice una prueba con el sistema operativo NOOBS versión 3.3.1 construido
arriba Debian Buster.

-----  DESCARGA  -----


Bajar el paquete escribiendo en un terminal:

wget https://github.com/allforonebusiness/allforonebusiness/releases/

-----  DEPENDENCIAS NECESITADAS  -----


Te necesitas la seguiente dependencias:

libssl1.1,libboost-all-dev,libevent-2,libgmp-dev


Por favor hay que instalarlas con:

sudo apt install libssl1.1 libboost-all-dev libevent-2 libgmp-dev


-----  INSTALACCIÓN  -----


Para instalar el programa hay que escribir el comando en el terminal:

unzip allforonebusiness_4.1.2.1_NOOBSBuster_QT.zip

cd AFO_Noobs/

sudo cp allforonebusiness* /usr/local/bin/

sudo cp test_allforonebusiness* /usr/local/bin/

Lanza la billetera escribiendo:

allforonebusiness-qt&

----- DESPUÉS INSTALACIÓN -----

después de la instalación hay que escribir en el terminal el programa:

./refreshnodes.sh

o

bash refreshnodes.sh


Esto necesita para mejorar las conexiones.

----- REFERENCES  -----

Author:  Davide Lustro

E-mail: buddandroid@gmail.com
