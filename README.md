# Docker Task
* Написать 2 Dockerfile с web сервисом прим. (nginx, apache), передать конфигурацию в контейнер прим. nginx.confб образы должны работать на разных портах.
* Собрать образы, используя double tagging ,положить собранные образы в локальное registry
* Написать docker-compose.yaml ,в котором должен быть создан сервис из 2 ранее созданных образов (использовать локальное registry ), с помощью которых можно публиковать статику, образы должны запускаться в разных сетях, но должны использовать 1 хостовой вольюм со статикой на двоих, а также образы должны быть ограничены по ресурсам (memory, cpu)

Итог:  через веб-браузер должна быть доступна статика на 2 опубликованных портах сервиса

# Result
* git clone https://github.com/skuzmin90/Docker.git
* cd Docker
* chmod +x start.sh
* ./start.sh
* Try to open localhost:8080 for nginx service and localhost:8081 - apache

