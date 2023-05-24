FROM nginx:latest

# Diretorio que se trabalha dentro do continer
WORKDIR /app

RUN apt-get update && \
    apt-get install vim -y 

COPY html/ /usr/share/nginx/html