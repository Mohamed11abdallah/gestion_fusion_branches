## Exercice 1 : Gestion des branches et fusion

### Objectif
Apprendre à créer, gérer et fusionner des branches dans Git, y compris la gestion des conflits de fusion.

### Étapes
1. Initialisation d'un dépôt Git.
2. Création d'une branche `feature1` et ajout du fichier `feature1.txt`.
3. Création et basculement sur la branche `feature2`, ajout du fichier `feature2.txt`.
4. Fusion de `feature2` dans `feature1`, gestion des conflits.

### Commandes Utilisées
- `git init`
- `git branch -m master feature1`
- `git checkout -b feature2`
- `git merge feature2`
- Résolution des conflits par édition manuelle.

### Résultat
Les branches ont été fusionnées avec succès, et les conflits dans `feature1.txt` ont été résolus.

---