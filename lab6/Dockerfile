# базовый образ nginx на alpine
FROM nginx:alpine

# копируем index.html в директорию
COPY index.html /usr/share/nginx/html/index.html

# порт 80 для доступа к веб-серверу
EXPOSE 80

# запуск по дефолту
CMD ["nginx", "-g", "daemon off;"]
