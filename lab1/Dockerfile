FROM nginx:latest

# RUN rm /etc/nginx/conf.d/default.conf

# COPY nginx.conf /etc/nginx/conf.d
COPY ./index.html /usr/share/nginx/html/index.html

EXPOSE 80 443

# Используйте базовую команду запуска Nginx (уже установлена в базовом образе)
CMD ["nginx", "-g", "daemon off;"]
