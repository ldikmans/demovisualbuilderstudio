FROM node:12

RUN mkdir -p /usr/src/api
COPY . /usr/src/api

WORKDIR /usr/src/api

RUN npm install

EXPOSE 7070
CMD [ "npm", "start" ]