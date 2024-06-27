FROM nginx:stable-alpine

COPY --chown=nginx \
    ./../nginx.conf /etc/nginx/conf.d/default.conf
COPY --chown=nginx \
    ./* /usr/share/nginx/errorpages/_error-pages