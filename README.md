Dev env for Symfony 4
===================

## Build and run containers

```
docker-compose build
```

```
docker-compose up -d
```

## Install SF4 website-skeleton

```
docker exec -it -u dev sf4_php bash
```

```
cd /home/wwwroot/sf4
composer create-project symfony/website-skeleton my-temp-folder
```
```
cp -Rf /home/wwwroot/sf4/my-temp-folder/. .
rm -Rf /home/wwwroot/sf4/my-temp-folder
```


