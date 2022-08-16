# Sample Weather App

## Installation

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm i
```

Build assets:

```sh
npm run dev
```

Setup configuration:

```sh
cp .env.example .env
Change your .env details to be able to connect to local database
```

Generate application key:

```sh
php artisan key:generate
```

Run database migrations:

```sh
php artisan migrate
```

Run the dev server (the output will give the address):

```sh
php artisan serve
```

Steps to access
```sh
1. Register an account
2. Login using that account
3. Enter Dashboard -> Weather 
4. Search a location and then add it into the list.
5. Can remove the list and then REFRESH.
```
