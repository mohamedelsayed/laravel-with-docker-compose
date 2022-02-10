# vip links:
https://www.youtube.com/watch?v=Ra1CetTcSeo 
https://webomnizz.com/containerize-your-laravel-application-with-docker-compose/ 

# to up docker compose:
docker-compose up -d

# to down docker compose:
docker-compose down

# to run bash "shell" on container docker:
sudo docker exec -it 449fa69a426c bash
 then run 
 composer install
php artisan key:generate
chmod 777 -R storage
php artisan migrate

# to restart docker:
sudo systemctl restart docker.service

# to get status docker:
sudo systemctl status docker.service

# to run laravel:
http://localhost:8080/

