FROM docker.jingzhuan.cn/web
MAINTAINER jackzzg@gmail.com
COPY php.ini /etc/php.ini
COPY nginx.conf /etc/nginx/nginx.conf 
COPY php-fpm.conf /etc/php-fpm.d/www.conf 
ENTRYPOINT ["/usr/bin/supervisord", "-c", "/etc/supervisord.conf"]
