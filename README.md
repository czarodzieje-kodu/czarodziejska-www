# czarodziejska-www
czarodziejekodu.pl webpage source code

## Development
### Prerequisites
* `docker` (prefarebly version 18.09.2) - [Get started with Docker](https://docs.docker.com/get-started/)
* `docker-compose` (prefarebly version 1.24.0) - [docker-compose overview](https://docs.docker.com/compose/overview/)

### Installation
1. Clone the repository
2. Run `docker-compose up -d`
3. After it finishes open `http://localhost` in your web browser to see Czarodzieje Kodu wordpress site

### Troubles?
* If `docker-compose` can't create and start containers make sure your already installed application does not use ports: 80, 3306 and 8080; for example stop any `apache2`, `ngnix` or `mysql` processes
