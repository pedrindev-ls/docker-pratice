FROM node:14-alpine  as todobackend
WORKDIR /backend
EXPOSE 3001
ADD node_modules.tar.gz /backend
COPY package*.json ./
ENTRYPOINT [ 'npm', 'start' ]