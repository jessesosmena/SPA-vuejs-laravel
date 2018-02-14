Demo: https://desolate-headland-52669.herokuapp.com

# A Vuejs-e-commerce application demo site,
# using json web token authentication/Laravel RESTful API server

# Backend:
php: 5.6.4,
barryvdh/laravel-cors: 0.11.0,
laravel/framework: 5.4,
laravel/tinker: 1.0,
laravel/passport 4.0,
stripe/stripe-php 5.7

How to use it
Clone the repository, cd to the directory, configure the .env file in the root of the folder, define your environment.

``` bash 
# install the packages
composer update

# used to add new tables, columns, or indexes to your database
php artisan migrate 

# Laravel development server started on http://localhost:8000. Now you can point your browser to http://localhost:8000
php artisan serve 

```
# Frontend:
webpack,
React v16,
React Router 4,
Redux,
Bootstrap 3 components

``` bash 
Build Setup

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
