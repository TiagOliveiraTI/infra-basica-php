FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY .infra/nginx/nginx.conf /etc/nginx/conf.d

RUN mkdir /var/www/html -p && touch /var/www/html/index.php