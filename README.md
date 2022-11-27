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
Tous d'abord, pour accéder au ce site, il faut d'abord créer un compte avec un nom et un code. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo2.png) Nous pouvons re-accéder ce site en utilisant ce nom et code. 
Et ensuite, dans le rubrique "Tableau de Pokemon", nous pouvons ajouter des nouveaus pokémons avec ses nom et description. Entrer le nom et description, et cliquer sur "Continuer", nous pouvons voir les information en bas. Par exemple : ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo1.png) En cliquant sur "Détail de pokémon", vous pouvez voir les informations détaillées de pokémon enregistré. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo4.png)
Dans le rubrique "Mon Profil", nous pouvons trouver les informations personnelles d'utilisateur. Et vous pouvez supprimer ce compte. ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo3.png)
Nous pouvons également se déconnecter en cliquant sur "Se déconnecter" en haut.
