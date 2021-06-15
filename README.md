[![CodeFactor](https://www.codefactor.io/repository/github/sergeevpasha/docker-php-cli/badge)](https://www.codefactor.io/repository/github/sergeevpasha/docker-php-cli)
[![Docker Image CI](https://github.com/sergeevpasha/docker-php-cli/actions/workflows/dockerimage.yml/badge.svg)](https://github.com/sergeevpasha/docker-php-cli/actions/workflows/dockerimage.yml)
# PHP-CLI

Built on PHP 8.0-CLI image

Main locale: en_US.UTF-8

## PHP Modules

* bcmath       
* Core
* ctype
* curl
* date
* dom
* exif
* fileinfo
* filter
* ftp
* gd
* gettext
* hash
* iconv
* imap
* intl
* json
* libxml
* mbstring
* openssl
* pcntl
* pcre
* PDO
* pdo_pgsql
* Phar
* posix
* readline
* redis
* Reflection
* session
* SimpleXML
* soap
* sodium
* SPL
* standard
* tokenizer
* xml
* xmlreader
* xmlwriter
* zip
* zlib

# Additional Software
* Cron

Example configuration for docker-compose.yml
```
app:
    image: uralenergotel/php-fpm:latest
    volumes:
        - ./:/var/www
    networks:
        - some-network
```
