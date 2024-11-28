# 🌄 Terrain en 3D - Environnement Interactif et Dynamique

Bienvenue sur **Terrain en 3D**, un projet interactif qui exploite les dernières technologies pour générer un paysage naturel dynamique. Ce terrain immersif vous permet de manipuler des éléments comme les montagnes, l'eau, et les dimensions globales à l'aide d'un panneau de contrôle personnalisable. Grâce à des shaders **GLSL** et des algorithmes procéduraux, ce projet offre un rendu visuel époustouflant et entièrement interactif.

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

## 🛠️ Technologies Utilisées

### Frontend
- **HTML5**, **CSS3**, **JavaScript (ES6+)**
- **Vite** : Build rapide pour un développement fluide.

### Rendu 3D
- **WebGL** : API pour le rendu graphique 3D dans le navigateur.
- **Three.js** : Simplification de la gestion des caméras, lumières, matériaux, et animations.
- **GLSL (Shaders personnalisés)** :
  - Simulation des vagues et des reflets dynamiques pour l’eau.
  - Effets atmosphériques (brouillard, ombres douces).
  - Transitions fluides entre les textures des reliefs.

### Génération procédurale
- **Perlin Noise** : Algorithme utilisé pour générer des paysages naturels et organiques.

### Interface utilisateur
- **Dat.GUI** ou panneau de contrôle personnalisé : Permet à l’utilisateur de modifier les paramètres en temps réel.

---


## ⚙️ Installation

### Prérequis
- **Node.js** (version 16 ou supérieure) : [Télécharger Node.js](https://nodejs.org/)
- Un gestionnaire de paquets (npm, inclus avec Node.js).

### Étapes d'installation et d'exécution

Copiez-collez les commandes suivantes dans votre terminal pour configurer et lancer le projet :

```bash
# Télécharger le repository

# Installer les dépendances
npm install

# Lancer le serveur local
npm run dev
