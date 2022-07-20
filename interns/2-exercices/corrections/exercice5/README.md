## Correction exercice 5

1. Réalisez un reset d'un ou plusieurs commits
-`git reset {id}` : remplacer {id} par l'identifiant d'un de vos commits

2. Regardez l'état de votre dépôt
- `git status`

3. Envoyez vos modifications sur votre dépôt distant
- Il faut d'abord ajoutés des fichiers dans l'index au préalable avec la commande `git add --all` par exemple
- Ensuite faire un commit `git commit -m 'refactor: update files'`
- Enfin on peut synchronisé avec le dépôt distant `git push`