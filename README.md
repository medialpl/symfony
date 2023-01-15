# Docker Symfony 6 boilerplate
Simple Docker PHP 8 boilerplate for Symfony projects

## Features
- PHP with built-in Web server
- Maria DB
- Symfony CMD
- Composer
- Node

## Requirements
- Docker 18.09.7 or newer
- Docker compose 1.27.4 or newer

## Usage
- `docker-compose up`

### New Symfony project
0) `cp .env-example` `.env`
1) `docker-compose up`
2) `docker exec -it medial_php bash`
3) `symfony new .`
