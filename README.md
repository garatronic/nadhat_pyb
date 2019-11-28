Carte NadHAT compatible Micropython
===================================
<p align="center">
  <img src="https://raw.githubusercontent.com/garatronic/nadhat_pyb/master/bandeau_f405_sd_700p.jpg" alt="NadHAT PYB405"/>
</p>

Vous êtes sur le dépôt des cartes NadHAT compatibles Micropython
Le site offciel se trouve là [garatronic.fr](http://www.garatronic.fr).

Carte NadHAT PYB405
-------------------

A completer


Installation du dépot micropython
---------------------------------
    $ sudo apt install gcc-arm-none-eabi
    $ git clone git://github.com/garatronic/micropython
    $ cd micropython/mpy-cross
    $ make
    $ cd ../port/stm32
    $ make BOARD=NADHAT_PYBF405


Téléchargement du noyan dans la carte
-------------------------------------

Après avoir placé la carte en mode téléchargement

    $ sudo make deploy BOARD=NADHAT_PYBF405
