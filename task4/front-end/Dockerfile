# Imagen nginx para el front-end
FROM nginx:latest
#
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end
#
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
# Port 9000
EXPOSE 9000