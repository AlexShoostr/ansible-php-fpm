---
Default values
---
php-fpm: "php7.3-fpm"
php-fpm_state: "present"
apt_update_cache: "yes"
php_modules:
    - php7.3-mbstring
    - php7.3-xml
    - php7.3-zip
    - php7.3-soap
    - php7.3-gd
    - php7.3-mysql
    - php7.3-dev
    - php-redis
    - php-pear
