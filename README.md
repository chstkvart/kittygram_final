[![Main kittygram workflow](https://github.com/andos12/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/andos12/kittygram_final/actions/workflows/main.yml)

#  Kittygram — это социальная сеть для обмена фотографиями пушистых котят (сфинксы мимо)

Проект состоит из бэкенда на Django и фронтенда на React. Вся инфраструктура контейнеризирована с помощью Docker и автоматически разворачивается на сервере через CI/CD на GitHub Actions.

## Стек технологии 

* Python + Django
* PostgreSQL
* Gunicorn
* Nginx
* React
* JavaScriptt

## Как развернуть проект

В проекте настроен автоматический пайплайн развертывания с помощью GitHub Actions (файл .github/workflows/main.yml). При любом push в ветку main происходит:

* Сборка и тестирование Docker-образов.

* Пуш собранных образов в Docker Hub.

* Деплой обновленных контейнеров на удаленный сервер по SSH.

* Автоматический запуск миграций и сбор статики на сервере.

## Автор

https://github.com/andos12
