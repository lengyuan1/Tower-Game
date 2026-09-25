# Tower Building Game

[中文](#-中文) | [Français](#-version-française)


---

## 🇫🇷 Version Française

Jeu web en 3D de construction de tour développé en JavaScript, permettant d'empiler des blocs de manière dynamique grâce au rendu WebGL.

### Description du projet
Ce projet est un mini-jeu d'adresse interactif dans lequel le joueur doit cliquer au moment opportun pour empiler des blocs mobiles. Le système gère l'alignement sur les axes et la découpe automatique des portions de blocs qui dépassent, augmentant la difficulté au fur et à mesure que la tour s'élève. 

### Architecture technique et fonctionnalités
- **Moteur 3D et Rendu :** Intégration de la bibliothèque Three.js pour la gestion de la scène, des lumières directionnelles, de l'éclairage ambiant et de la caméra orthographique.
- **Gestion des animations :** Utilisation de GSAP (TweenLite) pour assurer la fluidité des déplacements de caméra, des chutes de blocs coupés et des transitions de fin de partie.
- **Logique de jeu :** Implémentation complète des états du jeu (prêt, en cours, terminé, réinitialisation) et de la boucle de rendu via `requestAnimationFrame`.

### Lien de déploiement
[Jouer au jeu](https://lengyuan1.github.io/Tower-Game/)
---

## 🇨🇳 中文

基于 JavaScript 开发的 3D 网页叠塔小游戏，通过 WebGL 渲染实现动态方块堆叠。

### 项目描述
本项目是一个互动式街机风格的小游戏，玩家需要在合适的时机点击屏幕来堆叠移动中的方块。系统能够实时处理坐标轴上的对齐与超出部分的自动切割，随着塔楼的升高，游戏的挑战性也随之增加。

### 技术架构与核心功能
- **3D 引擎与渲染：** 集成 Three.js 库，用于管理场景、方向光、环境光以及正交摄像机。
- **动画控制：** 借助 GSAP (TweenLite) 确保摄像机平移、切块掉落轨迹以及游戏结束过渡动画的流畅性。
- **游戏逻辑：** 完整实现了游戏状态管理（就绪、进行中、结束、重置）以及通过 `requestAnimationFrame` 驱动的渲染循环。

### 线上部署
[线上玩](https://lengyuan1.github.io/Tower-Game/)



