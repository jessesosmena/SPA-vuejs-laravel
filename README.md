# A VueJs with Laravel SPA demo site,

# Demo: https://limitless-caverns-29210.herokuapp.com/index.html#/

To ensure you download everything, including
any submodules use git clone --recursive 

`
Frontend:
webpack: 2.6.1,
vue: 2.3.3,
vue-core-image-upload: 2.3.10,
vue-image-upload-resize: 1.1.4,
vue-resource: 1.3.4,
vue-router: 2.7.0,
vue-stripe-checkout: 0.0.4,
vue-stripe-elements: 0.2.3,
vuex: 2.3.1,
Bootstrap 3 components

`

How to use it,

``` bash 
Build Setup

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
`
Backend:
php: 5.6.4,
barryvdh/laravel-cors: 0.11.0,
laravel/framework: 5.4,
laravel/tinker: 1.0,
laravel/passport 4.0,
stripe/stripe-php 5.7

`

How to use it,

Clone the repository, 
cd to directory,
configure the .env file in the root of the project folder, 
define your environment

DB_CONNECTION=mysql,
DB_HOST=127.0.0.1,
DB_PORT=3306,
DB_DATABASE=homestead,
DB_USERNAME=homestead,
DB_PASSWORD=secret

MAIL_DRIVER=smtp,
MAIL_HOST=mailtrap.io,
MAIL_PORT=2525,
MAIL_USERNAME=null,
MAIL_PASSWORD=null,
MAIL_ENCRYPTION=null

``` bash 
# install the packages
composer update

# used to add new tables, columns, or indexes to your database
php artisan migrate 

# Laravel development server started on http://localhost:8000. Now you can point your browser to http://localhost:8000
php artisan serve 

```


