# Books entrypoint

### Project setup
Please clone this repository with the connected submodules. 

Later on head to `books-laravel` and set up the development environment (via docker-compose `docker-compose up -d` or manually fullfil the `.env` data). Install deps using `composer install` and start the development server via Artisan `php artisan serve`.

The next step to get this project running is the Angular client app located under `books-ng`. Head to this folder and proceed with the NPM install (`npm i`) and start the dev server `ng serve`. The app will use the `localhost:8000` as the API url (the default artisan port used in the development server).


