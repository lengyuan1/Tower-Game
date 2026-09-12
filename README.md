# Tower Building Game

Jeu web en 3D de construction de tour développé en JavaScript, permettant d'empiler des blocs de manière dynamique grâce au rendu WebGL.

## Description du projet
Ce projet est un mini-jeu d'adresse interactif dans lequel le joueur doit cliquer au moment opportun pour empiler des blocs mobiles. Le système gère l'alignement sur les axes et la découpe automatique des portions de blocs qui dépassent, augmentant la difficulté au fur et à mesure que la tour s'élève. 

## Architecture technique et fonctionnalités
- **Moteur 3D et Rendu :** Intégration de la bibliothèque Three.js pour la gestion de la scène, des lumières directionnelles, de l'éclairage ambiant et de la caméra orthographique.
- **Gestion des animations :** Utilisation de GSAP (TweenLite) pour assurer la fluidité des déplacements de caméra, des chutes de blocs coupés et des transitions de fin de partie.
- **Logique de jeu :** Implémentation complète des états du jeu (prêt, en cours, terminé, réinitialisation) et de la boucle de rendu via `requestAnimationFrame`.

## Lien de déploiement
[Jouer au jeu en ligne](https://lengyuan1.github.io/tower-game/)
