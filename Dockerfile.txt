# Use Nginx as the base image
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
