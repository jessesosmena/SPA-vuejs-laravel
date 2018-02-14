Demo: https://limitless-caverns-29210.herokuapp.com/index.html#/

# A Vuejs-e-commerce application demo site,
# using json web token authentication/Laravel RESTful API server

# Backend:
php: 5.6.4,
barryvdh/laravel-cors: 0.11.0,
laravel/framework: 5.4,
laravel/tinker: 1.0,
laravel/passport 4.0,
stripe/stripe-php 5.7

How to use it,
clone the repository, cd to the directory, configure the .env file in the root of the folder, define your environment.




``` bash 
# install the packages
composer update

# used to add new tables, columns, or indexes to your database
php artisan migrate 

# Laravel development server started on http://localhost:8000. Now you can point your browser to http://localhost:8000
php artisan serve 

```
# Frontend:
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

``` bash 
Build Setup

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
