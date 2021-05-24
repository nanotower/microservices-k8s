FROM node:12

WORKDIR /usr/src/app

COPY package.json ./

RUN npm i
# RUN npm audit fix

COPY . .

EXPOSE 8001

CMD [ "npm", "run", "prod" ]
