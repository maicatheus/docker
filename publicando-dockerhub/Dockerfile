FROM nginx

COPY html/ /usr/share/nginx/html

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["nginx","-g", "daemon off;"]

# docker build -t matheusmaicagoss/nginx-fullcycle . 
# faz o build da imagem a pardir deste Dockerfile
