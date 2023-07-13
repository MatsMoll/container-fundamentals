FROM nginx:1.24.0-alpine-slim
LABEL org.opencontainers.image.authors="mem@mollestad.no"
LABEL org.opencontainers.image.source=https://github.com/MatsMoll/container-fundamentals
LABEL org.opencontainers.image.description="Containter Fundamentals - Static Website Image"
LABEL org.opencontainers.image.licenses=APACHE2
LABEL server_type=edge_server
COPY config/nginx.conf /etc/nginx/
COPY web_content/ /var/www
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
