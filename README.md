# Laravel DataTables Starter Kit

This package starter kit is created to easily get started working with Laravel 5.5 and DataTables.

## Installation
1. Clone the repo.
`git clone https://github.com/yajra/laravel-datatables-starter.git myapp`

2. Install packages.
`composer install`

3. Install assets.
`npm install` or `yarn`

4. Configure your `.env` file and setup your database credentials.

5. Generate APP_KEY
`php artisan key:generate`

You can now visit your site via `http://myapp.dev` if you are using Laravel Valet.


## Compiling assets
Assets are managed via `npm` or `yarn`. Use the following commands to compile your assets:

```bash
yarn watch
npm run watch

yarn prod
npm run prod
```

See Laravel Mix for more details on asset management.
