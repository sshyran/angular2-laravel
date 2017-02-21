# Angular 2

This project was generated from Angular QuickStart [angular.io quickstart](https://angular.io/docs/ts/latest/quickstart.html).

Live demo at [dalenguyen.me](http://dalenguyen.me/angular2/http-observables/src/)

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#angular-laravel

- First clone via `git bash` or download.
- Go to your root folder and run this command
```
npm install
```
- Download [laravel-api](https://github.com/dalenguyen/laravel-api), which I used as a RESTful api.

- Before running your angular app, you need to check few things: app folder in `systemjs.config.js`, base and location from `index.html`, templateUrl and styleUrls from `Components`.

- Run your `angular` app by this command
```
npm start
```
and run your `laravel` api by this command
```
php artisan serve
```
You will see this app will load data from your api.

Enjoy!

This project is based on https://github.com/eliyas5044/angular-laravel
