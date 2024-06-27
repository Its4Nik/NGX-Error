FROM nginx:stable-alpine

COPY --chown=nginx \
    ./../nginx.conf /etc/nginx/conf.d/default.conf
COPY --chown=nginx \
    ./* \
    /opt/html/ghost /usr/share/nginx/errorpages/_error-pages