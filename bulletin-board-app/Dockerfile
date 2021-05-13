FROM node:10.10.0

WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . .
RUN mkdir /logs

CMD [ "npm", "start" ]
