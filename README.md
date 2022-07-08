# Snake3 : Projet_II2__ Marchesseau_Pietri
Mini-Projet de Systèmes embarqués (II2) - Master 1 E3A

Ce mini-projet qui résulte d'une collaboration entre Myriam Marchesseau et Carla Pietri consiste en un snake adapté au STM32F746G-Discovery.

Il est composé de 4 tâches : 
- defaultTask
- tache_snake : gère la longueur, la position et la direction du serpent, ses collisions avec les murs et les objets
- tache_affichage : gère l'affichage des objets et du serpent
- tache_game : crée un couple de coordonnées (x, y) aléatoire qui seront les coordonnées de l'objet, et gère le jeu : si le 
serpent entre en collision avec le mur ou lui-même, alors le jeu est terminé et une image "game over" apparaît sur l'écran. De plus, les autres tâches sont détruites.

Le serpent se déplace lorsqu'on agit sur le joystick.
