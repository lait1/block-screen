FROM nginx:latest

ADD ./default.conf /etc/nginx/conf.d/default.conf

COPY /etc/letsencrypt/live/discover-georgia.ru/fullchain.pem /etc/nginx/ssl/discover-georgia.ru/fullchain.pem
COPY /etc/letsencrypt/live/discover-georgia.ru/privkey.pem /etc/nginx/ssl/discover-georgia.ru/privkey.pem

WORKDIR /site