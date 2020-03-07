FROM nginx:latest

USER root
WORKDIR /etc/nginx

ARG CLIENT_PORT

# RUN apt-get update

# RUN apt-get install -y \
#     vim

COPY .docker/client-web-server/hosts conf.d/

CMD ["nginx", "-g", "daemon off;"]