# wp-sandbox

A Dockerized installation of Wordpress, Nginx and MySQL used for testing themes and plugins.

## Installation
1. Clone this repo
2. Create a 'wordpress' directory inside
3. Execute 'docker-compose up -d' for daemon mode or 'docker-compose up' to see process in console.

## Uninstall
1. Execute 'docker-compose down'
2. Remove all volume associated with this install 'docker volume rm'
3. Delete folder.
