Jeu de Pong avec un seul bouton de contrôle

Description

Ce projet est une implémentation du jeu de Pong sur une Raspberry Pi Pico avec un écran OLED. Le but du jeu est de renvoyer la balle avec votre palette en contrôlant sa position à l'aide d'un seul bouton. Lorsque le bouton est pressé, la palette se déplace vers le haut, et lorsqu'il est relâché, la palette descend. Le jeu oppose un joueur contre une IA qui contrôle la palette de l'autre côté de l'écran.

Fonctionnalités

Contrôle de la palette du joueur avec un seul bouton : appuyez pour déplacer la palette vers le haut et relâchez pour la déplacer vers le bas.
Déplacement automatique de la palette de l'IA pour suivre la balle.
Affichage de la balle et des palettes sur un écran OLED.
Système de score affichant le score du joueur et de l'ordinateur.
Réinitialisation du jeu après chaque point marqué avec une brève pause pour afficher les scores.
Matériel Requis

Raspberry Pi Pico
Écran OLED 128x64 (compatible I2C)
1 bouton-poussoir
Résistance (10kΩ pour la pull-up)
Câbles de connexion
Installation

Installer MicroPython sur la Raspberry Pi Pico (si ce n'est pas déjà fait).
Utiliser Thonny ou un autre éditeur compatible MicroPython pour programmer la Raspberry Pi Pico.
Copier le fichier contenant le code du jeu sur la Pico (par exemple pong.py).
Exécuter le script.
Utilisation

L'écran OLED affichera le terrain de jeu avec les palettes du joueur et de l'ordinateur, ainsi que la balle.
Appuyez sur le bouton pour déplacer la palette du joueur vers le haut.
Relâchez le bouton pour déplacer la palette du joueur vers le bas.
L'ordinateur contrôle automatiquement la palette de l'autre côté de l'écran.
Le jeu affiche les scores après chaque point et réinitialise la balle au centre du terrain.
Améliorations Possibles

Ajouter des effets sonores lors des collisions ou des points.
Ajouter un mode multijoueur avec deux boutons pour le contrôle des palettes.
Implémenter un système de difficulté croissante où l'IA devient plus rapide à mesure que le joueur marque des points.
Afficher le score sur un écran LCD ou un affichage 7 segments.
Ajouter un mode de jeu avec un temps limité pour marquer des points.

Auteurs

Alain Sliman
Raphaël Parone

