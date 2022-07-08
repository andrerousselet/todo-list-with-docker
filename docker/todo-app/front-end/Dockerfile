FROM node:14-alpine
EXPOSE 3000
WORKDIR /usr/src/app
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT ["npm start"]
