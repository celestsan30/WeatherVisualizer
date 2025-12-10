## 🌦️ Weather System Visualizer

**Projet 50 – Simulation & Visualisation**

## 📌 Présentation du Projet

Le **Weather System Visualizer** est une application interactive de simulation météorologique permettant de visualiser en temps réel des phénomènes climatiques tels que la **pluie, le vent, les nuages, la température et les orages**.

Ce projet a pour objectif de fournir un outil à la fois **pédagogique, technique et visuel**, destiné aux domaines du jeu vidéo, de l’animation et de la simulation scientifique.



## ❓ Problématique

Les systèmes météorologiques sont complexes et dynamiques. Il est souvent difficile de comprendre l’interaction entre les différents paramètres (température, humidité, vent, précipitations) à travers des modèles théoriques seuls.

**Problème posé :**

> Comment concevoir un outil simple, interactif et performant permettant de comprendre visuellement le fonctionnement d’un système météorologique en temps réel ?



## 🎯 Objectifs du Projet

* Simuler la **pluie** à l’aide d’un système de particules
* Simuler le **vent** sous forme de forces directionnelles
* Simuler les **nuages** par déplacement progressif
* Gérer la **température** et son influence sur les phénomènes météo
* Proposer une **interface graphique intuitive (ImGui)**
* Maintenir une **exécution fluide à 60 FPS minimum**
* Respecter strictement :

  * Les **conventions de nommage**
  * Le **Betty Doc**
  * Le **Betty Style**



## 🏗️ Architecture du Projet

```
weather_visualizer/
├── src/
│   ├── main.cpp
│   ├── App.hpp / App.cpp
│   ├── GUI.hpp / GUI.cpp
│   ├── Core/
│   │   ├── WeatherSystem.hpp / cpp
│   │   ├── RainSystem.hpp / cpp
│   │   ├── WindSystem.hpp / cpp
│   │   ├── CloudSystem.hpp / cpp
│   └── Utils/
│       ├── Math.hpp
│       └── Random.hpp
├── assets/
├── thirdparty/
├── build.py
└── README.md

```



## ⚙️ Technologies Utilisées

* **Langage :** C++
* **Interface Graphique :** ImGui
* **Système de Build :** Python (`build.py`)
* **Compilateur :** clang++



## ▶️ Compilation et Exécution

### 🔹 1. Compilation

```bash
python build.py
```

### 🔹 2. Exécution

```bash
./application
```


## 🎮 Contrôles Utilisateur

| Action                           | Contrôle |
| -------------------------------- | -------- |
| Modifier la température          | Slider   |
| Modifier la force du vent        | Slider   |
| Modifier l’intensité de la pluie | Slider   |
| Activer l’orage                  | Bouton   |
| Activer la neige                 | Bouton   |


## 🧠 Choix Techniques

* Utilisation d’un **système de particules** pour simuler la pluie
* Application de **forces vectorielles** pour le vent
* Architecture modulaire pour faciliter les extensions
* Interface ImGui pour une interaction rapide et intuitive
* Respect strict des conventions professionnelles de codage


## ✅ Conformité aux Exigences

* ✅ Nommage conforme (PascalCase, camelCase, mPascalCase, UPPER_SNAKE_CASE)
* ✅ Code documenté avec **Betty Doc**
* ✅ Mise en forme avec le **Betty Style**
* ✅ Architecture imposée respectée
* ✅ Projet prêt pour soutenance


## 🚀 Extensions Possibles

* Cycle **jour / nuit**
* Bruits sonores (pluie, tonnerre, vent)
* Carte météo avec zones climatiques
* Simulation du **changement climatique**
* Visualisation 3D simplifiée


## 👨‍🎓 Auteur

**Nom :** NLEND LIKENG Adalbert Celestin
**Filière :** Art Numérique / Intelligence Artificielle
**Projet :** Weather System Visualizer – Projet 50
**Année :** 2025
