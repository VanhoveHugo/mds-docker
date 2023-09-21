# Wordpress

## Description
This is a docker-compose file to run a Wordpress site with a MySQL database.

## How to use
1. Clone this repository
2. Run `docker-compose up -d` in the wordpress folder
3. Open your browser and go to `localhost:80`
4. Change the .env file to your configuration

## Notes
- The database is stored in the `db` folder
- The Wordpress files are stored in the `wordpress` folder
- PhpMyAdmin is available at `localhost:8080`

## Sources
- [Wordpress](https://hub.docker.com/_/wordpress)
- [MySQL](https://hub.docker.com/_/mysql)
- [PhpMyAdmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin)
- [Docker Compose](https://docs.docker.com/compose/)

