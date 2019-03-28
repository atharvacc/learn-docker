# USE an existing docker image as a base
FROM alpine

#Download and install dependency
RUN apk add --update redis
RUN apk add --update gcc

#Tell container what to do when we start 
CMD ["redis-server"]