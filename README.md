
# Laravel 10 project starter with authenctication system

A closed system starter with authenctication and user controll implements.




## How to install

Clone the repository

```bash
git clone hhtps://github.com/GuilhermeBiassio/laravel-project-authentication-starter

cd laravel-project-authentication-starter
```

Install project dependeces

```bash
composer install
```

Config the environment

```bash
copy .env-example .env
```

Config the auth routes

```bash
...

//System initial route
    Route::get('/', function () {
        return to_route('system_initial_route');
    });

    //Application prefix group 
    Route::prefix("app_prefix")->group(function () {

        //Authenticated routes

...
```






    
## Autors

- [@GuilhermeBiassio](https://www.github.com/GuilhermeBiassio)


#

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)


