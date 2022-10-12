# Hasura App
```
docker-compose up --build
```

http://localhost:9695 
http://localhost:8080/console

```
docker compose run --rm gcloud gcloud auth application-default login --project <使用するプロジェクトID>
```


## terraform
```
docker exec -it terraform_container /bin/sh

#コンテナ内で下記を実行してエラーが発生しないか確認
terraform init
terraform plan

#問題なければapplyを実行
terraform apply

#実行結果の確認
terraform show
```