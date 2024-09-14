+++

title="Présentation de la mécanique de la 2ème Machine de Jean Pierre"

author="Jean Pierre Rosset"

date="2016-01-01"

+++



Dans cette rubrique, je vais présenter mon 2ème prototype. Il a une course légèrement augmentée et équipé d'une fourche différente et munie d'un poinçon carré.
Je vais successivement amener les images au fur et à mesure de sa construction.

## Structure

Le fait de reposer les axes sur 2 plaques de base séparées permet de tendre la courroie simplement en dévissant le serrage des supports et en éloignant les 2 plaques et en revissant. 

![](p1.jpg)

![](p2.jpg)

![](p3.jpg)

Voici l'arrivée de l'axe Y (avance carton). Ce dispositif sera rehaussé par de colonnettes à la hauteur de la matrice de poinçonnage :

![](p4.jpg)

![](p5.jpg)

![](p6.jpg)

Avec les colonnettes et le rouleau entraîneur :

![](p7.jpg)

![](p8.jpg)

![](p9.jpg)

##Installation des Moteurs + Electronique

Voici avec les entraînements et les fins de course installés :

![](p10.jpg)

![](p11.jpg)

![](p12.jpg)

Les deux capteurs de fin de course sont des fourches optiques qui détectent les fins de course. Le HOMING (commande $H) du Grbl détecte la fin de course et la fourche de perforation avance et recule à très petite vitesse et s'arrête pile poil et toujours à la référence machine comme pour une CNC (essai au comparateur !).

Depuis cette référence, une commande simple (offset) paramétrée une fois pour toute, déplace le poinçon à la référence du carton et ainsi les ordres de la perforation peuvent être envoyés.

![](p13.jpg)


la matrice est réalisée dans un morceau d'acier HSS.
c'est usiné par électro-érosion. Le fil fait à peu près 0,2 mm de diamètre et pour ne pas avoir d'arrondi dans les coins, le fil rentre un petit peu dans l'angle pour supprimer l'arrondi.
Pour le poinçon, j'ai acheté chez RC-machines des barreaux en HSS et de 3x3 mm de section.

![](p14.jpg)

![](p15.jpg)

Avec le chemin du carton

![](p16.jpg)

![](p17.jpg)

![](p18.jpg)

![](p19.jpg)

Voici les images avec le câblage et sur la fourche les deux renforts :

![](p20.jpg)

##Chemin de carton

Le chemin de carton :

![](ch1.jpg)

![](ch2.jpg)

Le plan incliné en bois est introduit dans le tube de la fourche et est maintenu par des aimants. Le dispositif en tôle est placé sous la fourche et est maintenu par des aimants.
Le récipient est glissé sous la fourche et est aussi maintenu par un aimant.

## Performances de la machine


**10 août 2016** : Voici les informations de perforation :

3,2 mètres de carton perforés en 15 minutes 34 secondes et 7498 trous.

donc 934 secondes / 7498 = 0,1245 s par trou

(3,2 / 934) x 3600 = 12,33 m par heure (estimation pour cette densité de trous).

J'ai donc perforé avec les réducteurs de débit sur le vérin.

