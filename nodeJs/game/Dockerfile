FROM node:12.18.1
ENV NODE_ENV=production

WORKDIR /app/nodejs/game

COPY package*.json ./

RUN npm install --production

COPY . .

CMD [ "npm", "start" ]