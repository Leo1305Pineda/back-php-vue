# Backen Php Vue

Simple web application to manage a task list using Vue.js (Version 3) and other mentioned technologies.

## Installation

```bash
    sudo apt install php-zip php-xml php-gd php-mysql

    sudo apt install mysql-server
    sudo systemctl start mysql.service

    sudo mysql
    ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
    exit

    sudo apt install php8.1-amqp php8.1-common php8.1-gd php8.1-ldap php8.1-odbc php8.1-readline php8.1-sqlite3 php8.1-xsl php8.1-curl php8.1-gmp php8.1-mailparse php8.1-opcache php8.1-redis php8.1-sybase php8.1-yac php8.1-ast php8.1-dba php8.1-igbinary php8.1-mbstring php8.1-pgsql php8.1-rrd php8.1-tidy php8.1-yaml php8.1-bcmath php8.1-imagick php8.1-memcached php8.1-phpdbg php8.1-smbclient php8.1-uuid php8.1-zip php8.1-bz2 php8.1-ds php8.1-imap php8.1-msgpack php8.1-pspell php8.1-snmp php8.1-xdebug php8.1-zmq php8.1-cgi php8.1-enchant php8.1-interbase php8.1-mysql php8.1-psr php8.1-soap php8.1-xhprof php8.1-cli php8.1-fpm php8.1-intl php8.1-oauth php8.1-raphf php8.1-solr php8.1-xml


    mysql -uroot -p[PASSWORD_MYSQL]
    CREATE DATABASE phpvue;
    exit

    php artisan config:cache
    php artisan migrate:fresh --seed
    php artisan key:generate

    php artisan storage:link

    npm install
```

## QuickStart

```bash
    php artisan serve
```

```bash
    npm run watch
```

### Use email and password here database/seeders/UserSeeder.php