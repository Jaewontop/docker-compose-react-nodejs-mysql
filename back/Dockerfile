FROM node:14

WORKDIR /back
COPY package.json .
RUN npm install
COPY . .
CMD npm start
