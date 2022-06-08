# Projet MIPS - Jeu du Snake

Ce projet a été réalisé dans le cadre de l'UE architecture des ordinateurs de L2S3 à l'UFR de math info de Strasbourg.

## Pour commencer

### Pré-requis

- Le simulateur ``Mars4_5.jar`` disponible ici http://courses.missouristate.edu/kenvollmar/mars/


### Démarrage

- Pour lancer l'émulateur MARS, taper cette commande dans le terminal:

```
java -jar Mars4_5.jar
```

- Charger le fichier ``snake.s``, l'assembler puis aller dans l'onglet **Tools** pour lancer **Bitmap Display** ainsi que **Keyboard and Display MMIO Simulator**.

- Dans la fenêtre **Bitmap Display**, sélectionner **16** pour **Unit Width in Pixels** et **Unit Height in Pixels** puis **256** pour **Display Width in Pixels** et **Display Height in Pixels**.

- Finalement, cliquer sur les deux widgets **Connect to MIPS** et lancer l'exécution du programme.

![snakeAffichage](/uploads/32811232d35b303741cc5261bb467099/snakeAffichage.png)

## Pour jouer au snake

### Touches directionnelles

- Dans la fenêtre **Keyboard and Display MMIO Simulator** à la rubrique **Keyboard** vous pouvez entrer les touches directionnelles:
	+ **z** _haut_ 
	+ **q** _gauche_
	+ **s** _bas_
	+ **d** _droite_
	
**NB** : le serpent ne peut pas reculer sinon cela s'apparente à du cannibalisme

### Principe du jeu

- Lorsque le serpent mange de la nourriture _(carré rose)_:
	+ le serpent grandit
	+ un nouvel obstacle _(carré rouge)_ apparaît 
	+ le score est incrémenté

### Fin du jeu
- Le jeu se termine si le serpent se mord la queue, heurte un obstacle ou un mur. 

- À la fin du jeu, le score ainsi que le niveau atteint s'affichent dans la console.


## Auteurs

* **Justine Andreolli**  _alias_ [@jandreolli](https://git.unistra.fr/jandreolli)
* **Ambre LIS**  _alias_ [@ambre.lis](https://git.unistra.fr/ambre.lis)






