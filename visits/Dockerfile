#Base image
FROM node:alpine

#Set work directory
WORKDIR "/app"

COPY ./package.json .

#RUN Command
RUN npm install

#Copy everything else 
COPY . .

#RUN COmand
CMD ["npm",  "start"]

