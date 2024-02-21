FROM nginx:1.22

WORKDIR /var/www/html

ENV TZ=UTC

COPY ./docker/nginx/nginx.conf /etc/nginx/nginx.conf
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/
# COPY ./docker/nginx/*.conf /etc/nginx/conf.d/
