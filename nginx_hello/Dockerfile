# Используем официальный образ Nginx
FROM nginx:latest

# Копируем наш HTML-файл в директорию Nginx
COPY index.html /usr/share/nginx/html/index.html

# Открываем порт 80 (по умолчанию Nginx слушает этот порт)
EXPOSE 80

# Команда для запуска Nginx
CMD ["nginx", "-g", "daemon off;"]

