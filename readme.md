# Base Docker setup for PHP 7.4 / MariaDB / Nginx / Supervisor

## Available Scripts

In your own local environment, Type the following commands:

### `docker-compose -f docker-compose-dev.yml up -d`
To build the image and runs in background

### `docker exec -it covid-help-app bash`
To ssh on the image

### `composer install`
To install laravel packages

Runs the app in the development mode.<br>
Open [http://localhost:4000](http://localhost:4000) to view it in the browser.
Mysql port is located in `4100`.
