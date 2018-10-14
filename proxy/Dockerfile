FROM nginx

# Установка пакетов системы
RUN apt-get update && apt-get install -y \
    mc

# Настройка nginx
COPY ./default.conf /etc/nginx/conf.d