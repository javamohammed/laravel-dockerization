Create Laravel project with docker

docker-compose run --rm composer create-project laravel/laravel .
run container server Ngnix with 2 depends containers : php and mysql

docker-compose up server
To mange dependencies js in laravel project

docker-compose run --rm npm install
To manage laravel project

docker-compose run --rm artisan migrate
