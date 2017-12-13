Docker-compose template
=======================
## Requirements:
* docker
* docker-compose
### Services:
* nginx
* mysql
* pma
* php (contains installed git and composer)
## Configs:
All configs/logs/data for each service in appropriate service folder.
# Application files:
All application files folder contains in public_html
# RUN:
```bash
$ docker-compose up
```
## Links:
* web-server: http://127.0.0.1:8080/
* PMA: http://127.0.0.1:8081/