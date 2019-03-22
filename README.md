# alpine-with-php

docker run -p 80:80 -v ~/Desktop:/var/www/html -d -it test:latest --name alpine-with-php
docker exec -it alpine-with-php bash

docker start alpine-with-php
docker exec -it alpine-with-php bash