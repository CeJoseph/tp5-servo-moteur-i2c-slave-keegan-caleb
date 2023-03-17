Où on est rendu:
Reception du slave des commandes par I2C.

Étape de correction:
Vérifier le signal SCL du bus i2C vers la carte slave.
Ensuite verifier le signal SDA vers la carte du slave.

Pourquoi ça ne fonctionnait pas:
Notre hypothèse est que le soit le signal I2C ne se rend pas correctement vers la carte slave donc on verifiait le bus I2C vers le slave.
*Possiblement un problème avec les Pull-ups (Les changer et tester après)*
