## bKash Payment Gateway Integration with Laravel 7


## Install composer packages
```
$ cd laravel-bkash
$ composer install
```

## Create and setup .env file
```
make a copy of .env.example and rename to .env
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
```

## Migrate and insert records
```
$ php artisan migrate
$ php artisan tinker
$ factory(App\Order::class, 20)->create();
$ exit
```

## Put bKash sandbox credentials to config.json
```
create config.json file to storage/app/public
put credentials

```

