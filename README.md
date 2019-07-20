# Gatsby
## Les blocs de constructions

### Utilisez les starters Gatsby

Une fois que votre environnement de travail est prêt, vous allez créer votre premier site Gatsby à l'aide du starter "hello world".

Comment ça marche?
Lors de la création d'un nouveau site Gatsby, vous pouvez utiliser la structure de commande suivante pour créer un nouveau site basé sur tout starter Gatsby existant:

```console
gatsby new [SITE_DIRECTORY_NAME] [URL_OF_STARTER_GITHUB_REPO]
```

Dans notre cas ça donnera:
```console
gatsby new hello-world https://github.com/gatsbyjs/gatsby-starter-hello-world
```
Si vous omettez une URL à la fin, Gatsby générera automatiquement un site pour vous en fonction du starter par défaut.

Maintenant, rendez-vous sur votre projet hello-wordl créé puis ouvrez la page grâce à la commande suivante:
```console
cd hello-world
gatsby develop
```
### Familiarisation avec les pages Gatsby
Ouvrez le répertoire ```/src``` dans votre éditeur de code. A l' intérieur, il y a une seul répertoire: ```/pages```.

Ouvrez le fichier `src/pages/index.js`. Le code dans ce fichier crée un composant qui contient un seul div et du texte - «Hello world!





