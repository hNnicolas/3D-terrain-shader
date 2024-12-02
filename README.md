# 3D Terrain Shader 🌄 

Bienvenue sur **3D Terrain Shader**, un projet interactif qui exploite les dernières technologies pour générer un paysage naturel dynamique. Ce terrain immersif vous permet de manipuler des éléments comme les montagnes, l'eau, et les dimensions globales à l'aide d'un panneau de contrôle personnalisable. Grâce à des shaders **GLSL** et des algorithmes procéduraux, ce projet offre un rendu visuel époustouflant et entièrement interactif.

---

## 🔍 Description

**Terrain en 3D** vous propose d'explorer un paysage vivant, avec des fonctionnalités avancées :
- **Reliefs et eau dynamiques** : La structure des montagnes et de l’eau change en temps réel.
- **Contrôle utilisateur** : Ajustez les paramètres via un panneau interactif (GUI).
- **Rendu avancé avec GLSL** : Shaders personnalisés pour des effets visuels réalistes, comme les ondulations de l’eau et les reflets.
- **Adaptabilité en temps réel** : Augmentez ou réduisez la taille des reliefs et ajustez les détails des textures.

---

## 🚀 Fonctionnalités

- **Génération procédurale avancée** : Modélisation des montagnes et des reliefs basée sur l’algorithme Perlin Noise.
- **Panneau de contrôle personnalisé** :
  - Ajustez la hauteur et la largeur des montagnes.
  - Modifiez la vitesse et l’intensité des vagues dans l’eau.
  - Contrôlez les paramètres d’éclairage (position du soleil, intensité).
- **Shaders GLSL** :
  - Ondulations dynamiques de l’eau.
  - Effets de reflets sur les surfaces liquides.
  - Transition fluide entre les textures (herbe, roche, sable).
- **Éclairage et ombres dynamiques** : Simulation de cycles jour/nuit avec des ombres en temps réel.
- **Effets atmosphériques** : Brouillard volumétrique qui change avec la distance et l’altitude.

---

## 🛠️ **Technologies Utilisées**

| Technologie              | Description                                                                                       | Icône                                                                              |
|--------------------------|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| **JavaScript (ES6+)**    | Langage de programmation pour les interactions dynamiques.                                        | ![JavaScript](https://img.icons8.com/ios-filled/50/000000/javascript.png)          |
| **Vite**                 | Build rapide pour optimiser le développement avec un serveur performant.                          | <img src="https://vitejs.dev/logo.svg" width="50" />                               |
| **WebGL**                | API graphique permettant des rendus 3D interactifs dans le navigateur.                            | ![WebGL](https://img.icons8.com/ios-filled/50/000000/webgl.png)                    |
| **Three.js**             | Bibliothèque JavaScript facilitant la gestion des scènes 3D (caméras, lumières, matériaux, etc.). | ![Three.js](https://threejs.org/favicon.ico)                                       |
| **GLSL (Shaders)**       | Shaders personnalisés pour simuler des vagues, des reflets et des effets atmosphériques.          | ![GLSL](https://img.icons8.com/ios-filled/50/000000/code.png)                      |
| **Blender**              | Logiciel de modélisation 3D pour la création du modèle de casque.                                 | <img src="https://www.blender.org/favicon.ico" width="50" />                       |
| **Perlin Noise**         | Algorithme procédural pour générer des paysages naturels et organiques.| <img src="https://github.com/hNnicolas/raging-sea-project/raw/main/3dperlinnoise-variant2.jpeg" width="50" /> |


---


## ⚙️ Installation

### Prérequis
- **Node.js** (version 16 ou supérieure) : [Télécharger Node.js](https://nodejs.org/)
- Un gestionnaire de paquets (npm, inclus avec Node.js).


## 📚 **Installation**  

1. **Téléchargez le projet** :
   
2. **Installez les dépendances** :  
   Ouvrez un terminal dans le répertoire du projet et exécutez :  
   ```bash
   npm install

3. **Lancez le projet** :
   Ouvrez un terminal dans le répertoire du projet et exécutez :
   ```bash
   npm run dev
