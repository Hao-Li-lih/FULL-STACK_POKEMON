# Projet Full-stack : Wiki Pokemon


## Pour lancer l'application

1. Build images et containers:

```sh
$ docker-compose up -d --build
```

2. Migration des applications:

```sh
$ docker-compose exec backend aerich upgrade
```

Pour accéder le backend : [http://localhost:5000/docs](http://localhost:5000/docs)


Pour accéder le front : [http://localhost:8080](http://localhost:8080) 


## Introduction du Projet
Dans ce projet, nous avons créé un site de wiki pokémon. 

Tous d'abord, pour accéder au ce site, il faut d'abord créer un compte avec un nom et un mode de passe dans le rubrique "Créer un compte". ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo2.png) Nous pouvons re-accéder ce site en utilisant ce nom et code dans le rubrique "Se connecter". 

Et ensuite, dans le rubrique "Tableau de Pokemon", nous pouvons ajouter des nouveaus pokémons avec ses nom et description. Entrer le nom et description, et cliquer sur "Continuer", nous pouvons voir les information en bas. Par exemple : ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo1.png) 

En cliquant sur "Détail de pokémon", vous pouvez voir les informations détaillées de pokémon enregistré. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo5.png)
Quand utilisateur est éditeur de pokémon, nous changer les informations ou supprimer ce pokémon. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo6.png)
Et si l'utilisateur n'est pas éditeur d'un pokemon, il ne peut pas changer les informations de ce pokemon. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo4.png)

Dans le rubrique "Mon Profil", nous pouvons trouver les informations personnelles d'utilisateur. Et vous pouvez supprimer ce compte en cliquant sur le bouton. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo3.png)

Nous pouvons également se déconnecter en cliquant sur "Se déconnecter" en haut.

## Référence
1.https://github.com/DataTrainingOrg/fullstack-data-application

2.https://github.com/zy7y/watch-fastapi et https://juejin.cn/post/7015178908169404447

3.https://www.cnblogs.com/leiziv5/p/15416978.html

4.https://fastapi.tiangolo.com

5.https://github.com/testdrivenio/fastapi-vue

6.https://phillyharper.medium.com/svelte-fastapi-hello-world-2d545b901a34

7.https://github.com/tiangolo/full-stack-fastapi-postgresql
