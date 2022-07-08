FROM node:14-alpine
EXPOSE 3001
WORKDIR /usr/src/app
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT ["npm start"]
