# InfancyIT CRUD Genertor module Gen 2
### Boilerplate of Laravel with InfyOm Laravel Generator for AdminLTE Templates

### Follow on with the instructions given below to run this app with docker. Install docker and docker-compose if you don't have already. You can also run this app in your local environment if you wish.

# For Docker (need docker-compose)
## TO DO:
1. cd into laradock
2. edit docker-compose.yml to change settings of docker container as needed (default is good for this repo)
3. docker-compose build nginx mysql phpmyadmin
4. docker-compose up -d nginx mysql phpmyadmin (add other containers based on need)
5. docker-compose ps (check if the docker containers are running correctly)

## Now To Migrate:
1. docker-compose exec workspace bash (enter main docker workspace bash)
2. ls (You can see all the laravel app files as you have entered your docker workspace for this laravel project)
3. composer self-update
4. composer install (You can do composer update but you'll have to copy the .env file yourself)
5. php artisan migrate
6. php artisan db:seed

## Now you can browse to localhost to get started

from here you can run all the php artisan and composer commands. So do migrate and update composer if needed.

## NOTE: The composer inside the docker container is not the global host instance of composer. so it might not be updated depending the time you clone this repo. So run composer selfupdate from docker workspace bash if needed. Enjoy!

## USE:
http://labs.infyom.com/laravelgenerator/docs/5.3/getting-started (for generating scaffold and apis)
http://labs.infyom.com/laravelgenerator/docs/5.3/gui-interface (for gui-interface-builder)


# Cheerio!!
