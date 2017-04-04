FROM node:alpine

WORKDIR /srv

RUN npm install -g nodemon

VOLUME ["/srv"]

ENTRYPOINT ["nodemon", "-e", "js,pug"]
