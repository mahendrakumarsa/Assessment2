FROM node:10.23.1 as myassessment2_image

WORKDIR /opt/ng COPY .npmrc package.json ./ 

RUN npm install

COPY . ./ 

RUN node_modules/.bin/ng build --prod
