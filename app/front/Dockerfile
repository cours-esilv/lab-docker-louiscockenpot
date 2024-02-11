FROM nginx:latest

WORKDIR /app

COPY entrypoint.sh /app/

COPY index.html /usr/share/nginx/html/

RUN chmod +x ./entrypoint.sh

EXPOSE 80

ENTRYPOINT ["./entrypoint.sh"]
