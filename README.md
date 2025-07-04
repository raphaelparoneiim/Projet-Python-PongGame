# 🕹️ Pong – Raspberry Pi Pico Edition

Ce projet est une implémentation minimaliste et fun du célèbre jeu **Pong**, développée pour une **Raspberry Pi Pico** avec un écran **OLED 128x64**.  
Le joueur contrôle sa palette à l’aide **d’un seul bouton** : appui = monter, relâchement = descendre. L’autre palette est gérée par une **IA**.

---

## 🎮 Description

Le but est simple : empêcher la balle de franchir votre côté de l’écran.  
La partie se joue en **1v1 contre l’ordinateur** :

- 🟢 Le **joueur** contrôle une palette avec un **bouton unique**
- 🔴 L’**IA** contrôle automatiquement l’autre palette
- 🟡 L’écran OLED affiche le jeu, les scores et les rebonds
- ⚡ Un système de score est intégré avec **pause automatique** après chaque point

---

## ✨ Fonctionnalités

- 🎛️ Contrôle avec **un seul bouton** :  
  - Appuyer = palette vers le haut  
  - Relâcher = palette vers le bas  
- 🤖 **IA** qui suit la balle intelligemment  
- 📺 Affichage du terrain, des palettes et de la balle en temps réel  
- 🧠 Système de **score automatique**  
- 🔄 Réinitialisation automatique après chaque point marqué  

---

## 🧰 Matériel Requis

- 🧠 Raspberry Pi Pico  
- 🖥️ Écran OLED 128x64 (I2C)  
- 🔘 1 bouton-poussoir  
- 🔌 Câbles de connexion (Dupont)  
- 🧪 Breadboard (optionnel)

---

## ⚙️ Installation

1. Installer **MicroPython** sur la Raspberry Pi Pico  
2. Ouvrir **Thonny** (ou tout éditeur compatible MicroPython)  
3. Brancher la Pico en mode BOOTSEL  
4. Copier le fichier `pong.py` dans la mémoire de la Pico  
5. Exécuter le script

---

## ▶️ Utilisation

- L’écran OLED affiche :
  - La **balle**
  - Les **palettes**
  - Les **scores**
- Contrôle :
  - **Appui sur le bouton** → montée de la palette
  - **Relâchement** → descente de la palette
- Après chaque point, le score s’affiche brièvement puis une **nouvelle manche** démarre

---

## 👥 Auteurs

- 👨‍💻 Raphaël Parone
- 👨‍💻 Alain Sliman
