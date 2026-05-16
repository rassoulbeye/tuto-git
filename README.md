# Documentation du tuto Github avec Git

## Initialisation du dépôt

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit (bonnes pratiques)

```
Titre du commit

Description de notre commit avec des informations sur l'évolution du projet
```


## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Titre du commentaire"
git push origin main
```

##Création
```bash
git checkout -b nom_de_la_branche
```
Pour les bonnes pratiques, on va intégrer la notion de revue de code, c'est à dire que lorsqu'on a fini notre travail sur notre branche, on va faire une pull request pour que les autres membres de l'équipe puissent revoir notre code avant de le merger sur la branche principale.