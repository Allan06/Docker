FROM node:12.18.1
ENV NODE_ENV=production

WORKDIR /app/nodejs/chat

COPY package*.json ./

RUN npm install --production

COPY . .

CMD [ "npm", "start" ]