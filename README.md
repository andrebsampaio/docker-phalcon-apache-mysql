## Docker Phalcon-Apache-MySQL-PHPMyAdmin
How to use:

 1. Add db files into `dump` folder (they will be loaded to the db)
 2. Edit `docker-compose.yml`  and in the `volumes` argument of the www service, replace the current path with the path to your app
 3. run `docker-compose up`
 
 Relevant ports:
 App: 8000

 PhpMyAdmin: 8001
