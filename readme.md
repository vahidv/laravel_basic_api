<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About This Project

it's a simple made project for running an api call based projcts with laravel.

Empowers by use of favorite tymon jwt package. so It has some basic authentications like signup, login, logout and refreshing token.


POST signup
{{server_url}}/api/signup

api for register a new user. note that all the input parameters in example are required. author_name will be shown as creator of any post(image) if needed.

HEADERS

Acceptapplication/json
Content-Typeapplication/json

BODY

{
  "name":"your_name",
  "email":"your_mail@gmail.com",
  "password":"123456",
  "username":"your_username",
  "family":"your_family"
} 
 
 