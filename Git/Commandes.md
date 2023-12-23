## Configuration

La commande `git config` permet de configurer l’utilisateur.

```bash
git config --global user.email exemple@gmail.com
git config --global user.name exemple
```

La commande `git init` permet de créer un nouveau dépôt GIT.

```bash
git init
```

La commande `git clone` permet de lier un dépôt distant avec un répertoire local.

```bash
git clone /chemin/vers/dépôt
```

## Gestion

La commande `git status` permet d’afficher la liste des fichiers modifiés et à ajoutés ou validés.

```bash
git status
```

La commande `git log` permet d’afficher les logs.

```bash
git log
```

La commande `git diff` permet d’afficher les conflits.

```bash
git diff
```

La commande `git reset` permet de réinitialiser les données locales

```bash
git reset --hard
```

## Modification

La commande `git add` permet de sélectionner les fichiers qui seront pris en compte dans le prochain commit.

```bash
git add Nomdufichier
git add .
```

La commande `git commit` permet de valider les modifications apportées.

```bash
git commit -m “Description du commit”
```

La commande `git push` permet d’envoyer les modifications locales apportées à la branche principale associé.

```bash
git push origin nom-de-la-branche
```

La commande `git pull` permet de récupérer les modifications présentes sur le dépôt distant.

```bash
git pull
```

## Gestion de Branche

La commande `git branch` permet de faire plusieurs commandes associées aux branches.

```bash
git branch # Affiche les branches du repository
git branch nom-de-la-branche # Créer une branche
git branch --delete nom-de-la-branche # Supprime une branche
```

La commande `git checkout` permet de changer de branche.

```bash
git checkout nom-de-la-branche
```

La commande `git merge` permet de fusionner une branche dans la branche active.

Cette commande doit être effectué dans la branche qui va recevoir les documents et doit inclure le nom de la branche qui va disparaître dans la commande.

```bash
git merge nom-de-la-branche
```

La commande `git remote` permet de relier une branche à une autre.

```bash
git remote add origin nom-de-la-branche
```