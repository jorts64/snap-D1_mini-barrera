# snap-D1_mini-barrera
Control des de SNAP de un pas a nivell amb barrera amb D1 mini

![foto maqueta](/docs/maqueta1.jpg)

## Maquinari
Hem construit una senzilla maqueta d'un pas a nivell amb barrera, amb
* 2 servos 
* 2 sensors reflectius IR
* 2 semàfors de leds
* brunzidor (shield D1 mini)
* control wifi (D1 mini)

## Firmware D1 mini
Tot el sistema es controla amb una interfície web accessible per una xarxa creada pel propi D1 mini. Aquest [firmware](/pasanivellB1.ino) s'ha de carregar amb l'Arduino IDE.

## Llibreria snap
Hem implementat una [llibreria snap](/SNAP) per facilitar la codificació als alumnes de 2n d'ESO
