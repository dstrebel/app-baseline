FROM node:12-buster-slim

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install

COPY . .
ENV NODE_ENV "development"
EXPOSE 3012

CMD [ "npm", "run", "container" ]