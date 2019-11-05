# nginx-mysql-php
Use docker-compose to build nginx, mysql, php, phpmyadmin environment.

### Project tree
```
.
├── README.md
├── docker-compose.yml
├── nginx
│   └── default.conf
├── php
│   └── php.ini
└── web
    └── public
        └── index.php
```

### Ports
|  Server    |  Port  |
|------------|--------|
| Nginx      |  8000  |
| MySQL      |  8989  |
| PHPMyAdmin |  8080  |