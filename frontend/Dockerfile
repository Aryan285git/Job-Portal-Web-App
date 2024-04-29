FROM node:20-alpine

WORKDIR /app

COPY package.json .

RUN npm intall

COPY . .

EXPOSE 9000 

CMD [ "npm" , "start"]