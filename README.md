# PicDorsey/App

Custom docker image based from ubuntu 16.04 with php 7.0 fpm and nginx. Used in conjunction with mysql 5.7 to create a development environemnt.

## Usage
### Using docker
`docker run -d --name app -p 80:80 -v $(pwd):/var/www/html -e APP_ENV=development picdorsey/app`.


### Using docker-compose
Copy the contents of the `docker-compose.yml` file into your project and run `docker-compose up -d`.
