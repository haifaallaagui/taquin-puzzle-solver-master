# 🧩 Sliding Puzzle (Taquin Puzzle)

Ce projet est une implémentation du classique puzzle 3x3 à glissière (aussi connu sous le nom de **Taquin** ou **15 Puzzle**).  
Il permet de résoudre le puzzle automatiquement grâce à deux algorithmes : **DFS (Depth-First Search)** et **BFS (Breadth-First Search)**.

L'application propose une interface graphique intuitive avec laquelle l'utilisateur peut :

- Mélanger le puzzle
- Résoudre manuellement
- Laisser l’algorithme résoudre le puzzle automatiquement

---

## ✨ Fonctionnalités

- 🔀 **Shuffle** : Mélange aléatoirement les tuiles du puzzle
- 🧠 **Résolution automatique** : Utilise DFS ou BFS pour résoudre le puzzle
- 🎞️ **Animation en temps réel** de la résolution
- 🔁 **Réinitialisation** : Restaure l'état initial du puzzle
- 🖼️ **Interface graphique conviviale** via `Tkinter`

---

## 📦 Prérequis

Avant de commencer, assure-toi d’avoir installé :

- ✅ Python **3.x**
- ✅ La bibliothèque `Pillow` (fork de Python Imaging Library)

### 📥 Installation des dépendances

```bash
pip install pillow
