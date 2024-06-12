FROM nginx:1.17.8-alpine
COPY ./compose/production/nginx/default.conf /etc/nginx/conf.d/default.conf
COPY ./compose/production/nginx/ssl/key.pem /etc/ssl/nginx/key.pem
COPY ./compose/production/nginx/ssl/cert.pem /etc/ssl/nginx/cert.pem