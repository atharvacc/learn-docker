#Specify Base Image
FROM node:alpine

WORKDIR /usr/app
#Copy files
COPY ./package.json ./
#Install dependencies
RUN npm install

#Copy again
COPY  ./ ./
#Command at startup
CMD ["npm", "start"]

