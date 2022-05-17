FROM node:14-alpine  as todofrontend
WORKDIR /frontend
EXPOSE 3000
ADD node_modules.tar.gz /frontend
COPY package*.json ./
ENTRYPOINT [ 'npm', 'start' ]