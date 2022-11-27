# FastAPI和Vue，前端是做测试的，用的别人的模板，能改改就改改
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
Dans ce projet, nous avons créé un site de wiki pokemon. 
Tous d'abord, pour accéder au ce site, il faut d'abord créer un compte avec un nom et un code. Nous pouvons re-accéder ce site en utilisant ce nom et code. 
Et ensuite, dans le rubrique "dashbord", nous pouvons ajouter des nouveaus pokemons avec ses nom et description. Entrer le nom et description, et cliquer sur "Submit", nous pouvons voir les information en bas. Par exemple : ![image](https://github.com/Hao-Li-lih/FULL-STACK_POKEMON/blob/main/photo/photo1.png) 
Dans le rubrique "my profile", nous pouvons trouver les informations personnelles d'utilisateur. 
Nous pouvons également se déconnecter en cliquant sur "log out".
