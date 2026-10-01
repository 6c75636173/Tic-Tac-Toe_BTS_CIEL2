# ❌ Tic-Tac-Toe (Morpion) - Qt GUI

Un jeu de **Morpion (Tic-Tac-Toe)** avec une **interface graphique (GUI)**, développé dans le cadre d'un projet de cours en utilisant le framework **Qt**.

## 🚀 Fonctionnalités
* **Interface Graphique Intuitive :** Conçue avec Qt pour une expérience fluide.
* **Mode 2 Joueurs :** Affrontement classique au tour par tour (Joueur 1 vs Joueur 2).
* **Gestion du Score :** Suivi en temps réel des victoires, défaites et matchs nuls.
* **Détection Automatique :** Fin de partie instantanée en cas de victoire ou de match nul avec affichage du gagnant.
* **Réinitialisation Rapide :** Un bouton pour vider la grille et recommencer une nouvelle partie en un clic.

## 🛠️ Technologies Utilisées
* **Langage :** C++ (ou Python avec PySide/PyQt, à adapter selon votre projet)
* **Framework :** [Qt Framework](https://www.qt.io/)
* **Gestionnaire de build :** CMake / qmake

## 💻 Installation et Lancement

### Prérequis
* Un compilateur compatible C++ (GCC, Clang, MSVC)
* **Qt Creator** ou l'environnement Qt installé sur votre machine
* **CMake** (si utilisé pour le build)

### Cloner le projet
```bash
git clone https://github.com/VOTRE_PSEUDO/tic-tac-toe-qt.git
cd tic-tac-toe-qt
```

### Compilation (Ligne de commande avec CMake)
```bash
mkdir build && cd build
cmake ..
make
./TicTacToeQt
```
*Note : Vous pouvez également ouvrir directement le fichier `CMakeLists.txt` ou `.pro` dans **Qt Creator** et cliquer sur le bouton de lancement (Flèche verte).*

## 📁 Structure du Projet
```text
├── src/
│   ├── main.cpp          # Point d'entrée de l'application
│   ├── mainwindow.cpp    # Logique de l'interface graphique et des tours
│   └── mainwindow.h      # Déclarations des classes et des slots Qt
├── ui/
│   └── mainwindow.ui     # Design de la fenêtre (Qt Designer)
├── CMakeLists.txt        # Configuration du build CMake
└── README.md             # Documentation du projet
```

## 📝 Auteurs
* **Votre Nom** - *Développement principal* - [@votre_pseudo](https://github.com/votre_pseudo)

---
*Projet réalisé dans le cadre du cours de programmation.*
