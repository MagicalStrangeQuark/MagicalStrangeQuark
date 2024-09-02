<h6 align="center"><a href="https://www.heroku.com">✔️</a> Heroku</h6>

<p align="center">
    <a href="https://www.php.net">
        <img width="50%" src="https://raw.githubusercontent.com/MagicalStrangeQuark/MagicalStrangeQuark/master/assets/heroku.svg" alt="Heroku Icon">
    </a>
</p>

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

## Install the Heroku CLI

```bash
    brew tap heroku/brew && brew install heroku
```

## Login into the web platform and create a repository

## For existing repositories, simply add the heroku remote

```bash
    heroku git:remote -a agrosig-laravel-backend
```

```bash
    git push heroku master
```

## Enter into Heroku dyno container

```bash
    heroku ps:exec --app agrosig-laravel-backend
```

## Get database credentials

heroku pg:credentials:url

## Config Vars

heroku config:add APP_DEBUG=true

heroku config:add APP_ENV=production

heroku config:add APP_KEY=base64:gEl47g2kbXDrLTXL7BdB4FhXI8kXi2XMqsgyHgVNhbw=

heroku config:add DATABASE_URL=postgres://zbxmdmhdesebyy:2099042c45b0607c7e4212661ef8a58803815981d4498bd546affea100c210e2@ec2-34-192-174-151.compute-1.amazonaws.com:5432/d3l18d07ges3j6

heroku config:add DB_CONNECTION=pgsql

heroku config:add DB_HOST=ec2-34-192-174-151.compute-1.amazonaws.com

heroku config:add DB_PORT=5432

heroku config:add DB_DATABASE=d3l18d07ges3j6

heroku config:add DB_USERNAME=zbxmdmhdesebyy

heroku config:add DB_PASSWORD=2099042c45b0607c7e4212661ef8a58803815981d4498bd546affea100c210e2

heroku config:add SSLMODE=require

## Run migrations

```bash
    heroku run php artisan migrate
```

## Get current enviroment configuration

```bash
    heroku config
```
