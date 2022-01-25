FROM node:lts-alpine

WORKDIR /App
ADD node_modules.tar.gz ./
COPY ["src", "package*.json" "./"]
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]