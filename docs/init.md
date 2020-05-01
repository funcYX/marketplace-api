# Запуск проекта

## Забираем код
`git@github.com:funcYX/marketplace-api.git` или `https://github.com/funcYX/marketplace-api.git`

## Добавляем в хосты локальный домен
В `/etc/hosts` нужно добавить строчку `127.0.0.1	mp.loc`

## Стартуем докер
Из рутовой директории проекта выполняем
`docker-compose up`  или `docker-compose up -d` если хотим запустить в фоне

## Готово
Проект доступен локально по адресу 
`http://mp.loc:8085/`