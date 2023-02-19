<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Descripción del proyecto

Este proyecto, denominado "Clon de Reddit" es la representación de un clon de la red social Reddit. Está representado por una API hecha en Laravel y posee una batería de test para la misma, dónde se comprueban las siguientes cosas

- Fetch a todas las comunidades sin login
- Fetch a una comunidad sin login
- No se puede crear una comunidad sin nombre
- Usuario puede crear una comunidad
- Anónimo no puede crear una comunidad
- Usuario puede actualizar una comunidad
- Usuario puede eliminar una comunidad
- Devuelve un error json si la comunidad no existe

Posteriormente, se comprueba las restricciones aplicadas con Sanctum usando el programa Postman. En Postman realizaremos las peticiones a la API, para comprobar que las restricciones funcionan correctamente.

## Instalación

Para instalar el proyecto, se debe clonar el repositorio en la carpeta deseada. Una vez clonado, se debe ejecutar el comando `composer install` para instalar las dependencias del proyecto. Posteriormente, se debe ejecutar el comando `php artisan migrate` para crear las tablas en la base de datos. Por último, se debe ejecutar el comando `php artisan serve` para levantar el servidor de Laravel.

Para ejecutar los test, se debe ejecutar el comando `php artisan test --filter CommunityTest`.
