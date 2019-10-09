FROM node:latest

COPY ./package.json /srv/app/package.json

WORKDIR /srv/app/

RUN npm install

COPY ./ /srv/app/

EXPOSE 8081

CMD ["npm", "run", "start"]