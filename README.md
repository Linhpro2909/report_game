## Slotgen Laravel (Current: Laravel 8.*)

## First install:
Upload your code and rename file `.env.example` to `.env` and modify your database connection, then run command:
```
COMPOSER_MEMORY_LIMIT=-1 composer install
php -d memory_limit=-1 C:/ProgramData/ComposerSetup/bin/composer.phar install
npm install
php artisan migrate
php artisan db:seed
php artisan key:generate
npm run dev
php artisan serve
php artisan clear-compiled
composer dumpautoload
php artisan vendor:publish --tag=public --force
```

## Reload seeder:
```
composer dump-autoload
```

## Clear cache:
```
php artisan config:clear
php artisan cache:clear

redis-cli
FLUSHDB
```

## Create new model
```
https://harish81.github.io/infyom-schema-generator/
php artisan infyom:scaffold Player --fieldsFile=resources\model_schemas\Player.json
```


## Gen RTP:
```
php artisan slotgen:rtp
```

## Demo Credentials
Owner/Developer login:
```
owner@slotgen.com
sl@tgen
```

Admin login:
```
admin@slotgen.com
sl@tgen
```

Manager login:
```
slotgen:slotgen
slotsupper:slotgen
slotsenior:slotgen
master:slotgen
agent:slotgen
```

Sub Account login:
```
slotgensub:slotgen
slotsuppersub:slotgen
slotseniorsub:slotgen
mastersub:slotgen
agentsub:slotgen
```

Game Member:
```
user01:slotgen
user02:slotgen
user03:slotgen
user04:slotgen
user05:slotgen
```

### More Infomation
Laravel Boilerplate with [AdminLTE](https://adminlte.io/) Theme with [InfyOm Laravel Generator](https://github.com/InfyOmLabs/laravel-generator).
Following things are ready to be used directly with AdminLTE Theme.
https://adminlte.io/themes/AdminLTE/pages/UI/general.html

### License

NHutCorp: [https://nhutcorp.com](https://nhutcorp.com)
#   r e p o r t _ g a m e  
 