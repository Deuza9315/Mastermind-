# Mastermind - Ultimate Edition 🧩

Bienvenue dans l'édition ultime du **Mastermind**, un jeu de réflexion classique entièrement revisité avec une interface moderne, immersive et dynamique. Ce projet a été réalisé dans le cadre d'un module d'IHM (Session PHP L3).

## 🎮 Fonctionnement du Jeu

Le Mastermind est un jeu de déduction où vous devez déchiffrer un code secret généré aléatoirement par l'ordinateur.

### Objectif
Deviner la combinaison exacte de **4 pions** colorés cachés, en un nombre limité de tentatives.

### Déroulement d'une partie
1. **Choix des couleurs** : À chaque tour, sélectionnez 4 couleurs dans la palette disponible en bas de l'écran pour composer votre proposition.
2. **Validation** : Une fois votre ligne complétée, le jeu compare votre proposition au code secret.
3. **Indices (Feedback)** : Des petits pions indicateurs apparaissent à droite de votre ligne :
   - ⚫ **Pion Noir** : Indique qu'une couleur est **correcte et bien placée**.
   - ⚪ **Pion Blanc** : Indique qu'une couleur est **correcte mais mal placée**.
   - *Note : L'emplacement des indices ne correspond pas forcément à l'ordre des pions de votre proposition.*

### Victoire et Défaite
- **Victoire** : Vous gagnez si vous trouvez la combinaison exacte (4 pions noirs).
- **Défaite** : Vous perdez si vous n'avez pas trouvé le code après l'épuisement de toutes les tentatives.

---

## ✨ Fonctionnalités Premium

Ce projet se distingue par une expérience utilisateur riche et personnalisable :

### 🎭 Thèmes Immersifs
Changez l'ambiance visuelle du jeu en un clic :
- **Casino 🎰** : Ambiance Las Vegas avec tapis vert et jetons de poker.
- **Arcade Rétro 👾** : Style pixel-art avec un arrière-plan animé "Space Invaders".
- **Galaxy 🌌** : Voyagez dans l'espace avec des effets de nébuleuses.
- **Forêt Enchantée 🌿**, **Désert & Sable 🏜️**, **Océan 🌊**, **Noël 🎄**.

### 🎨 Skins de Pions
Personnalisez vos pions au-delà des simples couleurs :
- **Planètes 🪐** : Mars, Terre, Saturne, Jupiter...
- **Mario Bros 🍄** : Retrouvez les icônes du célèbre jeu.
- **Zèbre 🦓**, **Fruits 🍎**, **Bonbons 🍬**, **Galaxie ✨**.

### 💰 Boutique et Économie
- Gagnez des **Jetons** en jouant et en gagnant des parties.
- Utilisez vos jetons dans la **Boutique** pour débloquer de nouveaux thèmes et skins exclusifs.

### 🔐 Authentification & Sauvegarde
- Système de **Connexion / Inscription** pour sauvegarder votre solde de jetons et vos objets débloqués.
- Mode Admin disponible pour les tests.

---

## 🚀 Installation et Lancement

Le projet est conçu pour être exécuté directement dans un navigateur moderne sans serveur complexe (bien qu'une configuration PHP puisse être nécessaire pour certaines fonctionnalités de session avancées selon l'évolution du projet).

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Deuza9315/Mastermind.git
