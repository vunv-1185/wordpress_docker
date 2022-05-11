### Install with docker

* Clone project
```
git clone https://github.com/vunv-1185/wordpress_docker.git
```

* Copy `.env.example` file to `.env`
```
cp .env.example .env
```

* Set these environment variable in `.env` file
```
MYSQL_ROOT_PASSWORD=Aa@123456
MYSQL_USER=wordpress
MYSQL_PASSWORD=Aa@123456
MYSQL_DATABASE=wordpress

PMA_WEB_PORT=8001
PMA_HOST=wordpress_mariadb
PMA_USER=wordpress
PMA_PASSWORD=Aa@123456
```

* Run docker
```
docker-compose up -d
```

* Default access at: [localhost:8000](http://localhost:8000)
