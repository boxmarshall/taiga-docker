FROM nginx:1.19-alpine

# Install the required packages
RUN apt-get update -y

RUN apt-get install curl -y

COPY ./taiga.conf /etc/nginx/conf.d/default.conf
