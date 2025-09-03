# Site Collaboratif
## Commandes Git utilisées

### Initialisation
- `git init` - Initialiser le dépôt
- `git config user.name` - Configurer l'utilisateur
- `git add README.md` - Ajouter fichier
- `git commit -m "message"` - Premier commit
- `git tag v1.0-init` - Créer un tag

### Branches et fusion
- `git branch develop` - Créer branche
- `git switch develop` - Changer de branche  
- `git merge feature` - Fusionner branche
- `git rebase develop` - Rebaser branche

### Collaboration
- `git remote add origin` - Lier dépôt distant
- `git push -u origin develop` - Pousser branche
- `git clone` - Cloner dépôt
- `git pull origin develop` - Mettre à jour local

### Commandes avancées
- `git revert` - Annuler commit
- `git reset` - Réinitialiser
- `git restore` - Restaurer fichier
- `git log --oneline --graph --all` - Voir historique