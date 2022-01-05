FROM node

WORKDIR /app/backend

COPY package*.json ./

RUN npm install

RUN npm install -g nodemon

RUN npm install axios

ADD . .

EXPOSE 8080

CMD nodemon index.js
