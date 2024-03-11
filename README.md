## О приложении
Currency Exchange API - это надежный инструмент для получения актуального курса валюты от Центрального Банка. Мы предоставляем простой и удобный способ получения данных о курсах валют, которые обновляются ежедневно. Наш API обеспечивает быстрый и безопасный доступ к этой информации, что позволяет вашему приложению интегрировать ее с легкостью.

- [Документация REST API](http://api.exchange-rate.test/documentation).

## Установка


```
    docker-compose build
```

После 

```
    docker-compose up -d
```
 

```
    cp .env.example .env
```

Для установки проекта на вашем в контейнере, выполните простую команду, которая автоматизирует все необходимые процессы вместо вас.

```
    composer install
```

```
    php artisan backend-app:install
```

В этой команде включены:
- **[Установка зависимостей Composer Packages](https://laravel.com/docs/4.2#install-composer)**
- **[Генерация ключа для проекта.](https://laravel.com/docs/7.x/installation#configuration)**
- **[Миграция таблиц базы данных.](https://laravel.com/docs/9.x/migrations#running-migrations)**
- **[Заполнение базы данных значениями по умолчанию.](https://laravel.com/docs/9.x/seeding#running-seeders)**
- **Оптимизация.**
- **Копирование примера файла окружения в файл окружения.**
- **[Генерация документации Swagger.](https://swagger.io/)**

## Обзор репозитория

Предоставьте обзор структуры каталога и файлов, например:
```
├── app
├── bootstrap
├── config
│   ├── admin.php
│   ├── app.php
│   ├── auth.php
│   ├── backup.php
│   ├── broadcasting.php
│   ├── cache.php
│   ├── cors.php
│   ├── database.php
│   ├── filesystems.php
│   ├── hashing.php
│   ├── l5-swagger.php
│   └── logging.php
│   └── mail.php
│   └── queue.php
│   └── sanctum.php
│   └── services.php
│   └── session.php
│   └── translation-manager.php
│   └── view.php
├── database
│   └── factories
│   └── migrations
│   └── seeders
├── public
├── resources
├── routes
├── storage
└── tests
├── .env.example
├── .gitignore
├── composer.json
├── composer.loc
├── data-preparation
├── README.md
└── phpunit.xml
```

## Конфигурация

В проекте присутствует файл окружения (.env), который предоставляет доступ к настройкам проекта. Эти настройки включают в себя конфигурацию базы данных, данные проекта (название, URL), настройки почты и Redis. Для установки значений конфигурации, отредактируйте этот файл.

## Обо мне

- **Контакты**
  - ***[LinkedIn](https://www.linkedin.com/in/shahinyanm/)***
- Email
  - ***[shahinyanm@gmail.com](shahinyanm@gmail.com)***

