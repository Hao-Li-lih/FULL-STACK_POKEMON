# FastAPI和Vue，前端是做测试的，用的别人的模板，能改改就改改



## 如何部署项目-Docker

1. Build images 和 建containers:

```sh
$ docker-compose up -d --build
```

2. 应用迁移（基本不会用到，但是人家模板里面加了。我试了试，加不加都一样）:

```sh
$ docker-compose exec backend aerich upgrade
```

然后看后台以下网址： [http://localhost:5000/docs](http://localhost:5000/docs)


前端网址 [http://localhost:8080](http://localhost:8080) 
