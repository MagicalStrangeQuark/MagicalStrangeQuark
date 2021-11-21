<h6 align="center">JWT Guide Link <a href="https://www.avyatech.com/rest-api-with-laravel-8-using-jwt-token">🔐</a></h6>

<p align="center">Guide link to implement JSON Web Token (JWT) authentication</p>

<h6 align="center">JWT</h6>

```bash
    composer require tymon/jwt-auth

    php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"

    php artisan jwt:secret

    php artisan make:middleware JwtMiddleware
```

<h6 align="center">Tests</h6>

```bash
    php artisan make:test JWTAuthTest
```