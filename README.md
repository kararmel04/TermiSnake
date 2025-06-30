# TermiSnake 🐍

Ce projet est une implémentation simple mais évolutive du célèbre jeu **Snake**, 
jouable dans un terminal Linux. Codé en **C**, il se décline en quatre versions, chacune ajoutant une nouvelle mécanique de gameplay.

---

## 🔧 Compilation

Assurez-vous d’avoir un compilateur C (comme `gcc`) installé. Pour compiler, tapez :

```bash
gcc -o snake main.c
```

## 🕹️ Versions du jeu

### Version 1 : Mouvement Automatique
- Saisie des coordonnées de départ X et Y au lancement.
- Le serpent (O pour la tête, X pour le corps) se déplace automatiquement vers la droite.
- Appuyer sur a pour arrêter.

### Version 2 : Contrôle Manuel
- Coordonnées initiales fixes : (20, 20).
- Le joueur contrôle le serpent avec z, q, s, d.
- Appuyer sur a pour arrêter.

### Version 3 : Plateau avec Pommes
- Ajout d’un plateau de jeu de 80 x 20 caractères.
- Bordures représentées par #.
- Apparition aléatoire de pommes (6) que le serpent peut manger.

### Version 4 : Téléportation et Obstacles
- Chaque bordure contient un trou au centre qui téléporte le serpent sur la face opposée.
- Apparition aléatoire de 4 obstacles de taille 5 x 5 (composés de #).
- Les obstacles apparaissent à au moins deux cases de distance du serpent.
