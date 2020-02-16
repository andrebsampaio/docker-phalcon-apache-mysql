## How to use:

 1. Add db files into `dump` folder (they will be loaded to the db)
 2. Edit `docker-compose.yml`  and in the `volumes` argument of the www service, replace the current path with the path to your app
 3. run `docker-compose up`
 
| Service | Port  |
|--|--|
| App | 8000 |
|PhpMyAdmin| 8001|

Note:
When communicating between containers might be necessary to specify the IP address.
