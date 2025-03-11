# First_XR_Engine

## Introduction
First_XR_Engine est un moteur de réalité augmentée développé en C++ permettant la conception d'applications en AR, notamment pour les jeux vidéo. Il repose sur OpenGL et utilise plusieurs bibliothèques pour la gestion graphique et l'interface utilisateur.

## Fonctionnalités
- 🎮 Rendu 3D avec OpenGL
- 🕶️ Gestion de l'affichage AR
- 🖥️ Interface utilisateur interactive avec ImGui
- 🎮 Support de SDL3 pour la gestion des entrées et fenêtres
- 🔧 Intégration de Glad2 pour le chargement des extensions OpenGL
- ⌨️🖱️ **Ajout d'événements clavier et souris** :
  - Gestion des appuis sur les touches du clavier
  - Récupération des clics souris et de la position du curseur
  - Affichage des entrées en temps réel dans l'interface ImGui
- 🖼️ **Amélioration de l'interface ImGui** :
  - Ajout de nouvelles fenêtres interactives
  - Affichage dynamique de texte et de boutons
  - Conditions pour afficher ou masquer des éléments selon les interactions utilisateur

🛠️ **Ces ajouts permettent une meilleure compréhension du fonctionnement des entrées utilisateur et facilitent le debug via l'interface graphique.**

## Prérequis
Avant d'utiliser First_XR_Engine, assurez-vous d'avoir installé :
- 💻 **Windows/Linux** (Testé principalement sur Windows)
- 🛠️ **Visual Studio ou un compilateur C++ compatible**
- 🔨 **Premake5** pour la génération des fichiers de projet

## Installation et Génération
1. Clonez le dépôt :
   ```sh
   git clone https://github.com/votre-repo/First_XR_Engine.git
   cd First_XR_Engine
   ```
2. Générez les fichiers de projet avec **Premake5** :
   ```sh
   gen.bat
   ```
3. Compilez le projet :
   ```sh
   build.bat
   ```
4. Exécutez l'application :
   ```sh
   run.bat
   ```

## Bibliothèques Utilisées
- **OpenGL** : API graphique pour le rendu 3D.
- **SDL3** : Gestion des entrées, fenêtres et événements.
- **ImGui** : Interface utilisateur graphique pour la création d'outils interactifs.
- **Glad2** : Loader OpenGL pour gérer les extensions.

## Structure du Projet
```
First_XR_Engine/
├── build/              # Dossier de compilation
│   ├── bin/           # Fichiers binaires compilés
│   ├── obj/           # Objets compilés
├── External/          # Bibliothèques externes
│   ├── Libs/         # Contient les dépendances (Glad2, ImGui, SDL3...)
├── First_XR_Engine/   # Code source principal
├── .gitignore         # Fichiers à exclure de Git
├── build.bat          # Script de compilation
├── gen.bat            # Script de génération du projet
├── run.bat            # Script d'exécution
├── premake5.lua       # Configuration Premake5
├── README.md          # Documentation
```

## Contribution
Les contributions sont les bienvenues ! Pour proposer des modifications :
1. Forkez le projet.
2. Créez une branche.
3. Faites vos modifications et soumettez une Pull Request.

## Licence
Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
