# USE an existing docker image as a base
FROM alpine

#Download and install dependency
RUN apk add --update redis

#Tell container what to do when we start 
CMD ["redis-server"]