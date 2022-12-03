# Open_beehive_scale_V0.2

Balance connectée autonome sur réseau LORA/LORAWAN

1/Exemple de balance en profilé alu de type Bosch Rexroth utilisable sur fond de ruche Nicot.

- 2x profilé alu 60x30mm fente 8mm de 480mm
- 4 x profilé alu 30x30mm fente 8mm de 430mm
- 1 jauge de contrainte BOSCHE H40A de 150 kg
- 24 x equerre de fixation interne profilés 8 mm

Pièces imprimées 3D

- 4 x capuchons pour profilés du bas de la balance.
- 2 x capuchons arrière pour maintenir le fond de ruche Nicot.
- 1 x capuchon gauche et 1 x capuchon droit pour maintenir le fond de ruche Nicot.
- 2 x entretoises à placer entre les profilés 60x30 et la jauge de contrainte.
- 8 x vis tête cylindrique bombée M8x40mm
- 4 x vis tête cylindrique bombée M8x30mm

Prévoir un taraud M5 pour fileter de chaque coté deux profilés alu 30x30mm

![This is an image](https://github.com/Ratamuse/Open_beehive_scale_V0.2/blob/master/Plan%20balance/Balance%20ruche.JPG)

2/ Circuit imprimé dessiné autour de la carte Arduino MKRWAN 1310
- Possibilité de brancher jusqu'à:
- 4 balances (circuit HX711)
- 4 sondes externe de température/humidité SHT40
- 4 sondes de température DS1820b
- 1 brocche I2C spare
- 1 broche ADC spare
- 1 GPS QUECTEL L80-M33
- 1 batterie Lipo
- 1 panneau solaire 1W

Recharge de la batterie par un chargeur solaire MPPT. 
Surveillance de la température/humidité de la carte par un capteur SHT4X soudé sur la carte.
Jauge batterie I2C
Baromètre MS5611
Lecteur de carte SD
Capteur de mouvement (contacteur à bille) pour créer un alarme.

![This is an image](https://github.com/Ratamuse/Open_beehive_scale_V0.2/blob/master/Electronique%20balance/Ruche%20dessus.jpg)

![This is an image](https://github.com/Ratamuse/Open_beehive_scale_V0.2/blob/master/Electronique%20balance/Ruche%20dessous.jpg)








