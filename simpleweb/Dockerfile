# specifyy a base image
FROM node:14-alpine

#change working directory, if directory doesnt exist docker will create it
WORKDIR /usr/app 

#install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#default command
CMD ["npm", "start"]