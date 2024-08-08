FROM nginx:1.23-alpine
COPY --chown=nginx:nginx ./src /var/www/
WORKDIR /var/www/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
