# 環境構築  
### コンテナ構築  
```
$ docker-compose build
```
  
### コンテナ起動
```
$ docker-compose up -d
```

### DjangoとMySQL接続
```
$ docker-compose exec app ./manage.py migrate
```

### Djangoプロジェクト起動
```
$ docker-compose exec app /workspace/manage.py runserver
```
