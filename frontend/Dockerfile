# syntax=docker/dockerfile:1
FROM nginx:1.25-alpine

# Copy Nginx config and static assets
COPY frontend/nginx.conf /etc/nginx/nginx.conf
COPY frontend/index.html /usr/share/nginx/html/index.html


EXPOSE 80