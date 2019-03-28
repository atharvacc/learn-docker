# Dockerize web app that counts how many times a page is visited

## Build multiple contains containing Node and move output to redis-server
## Example: Visits
## 'docker run redis'   (Won't work until you set up compose)

# Using Docker compose
-   Look at the docker compose file with description
-   Create 2 containers on same network, w free access to        communicate w each other

-   docker-compose up (equivalent of docker run)
-   docker-compose build  . (equivalent of 'docker build .' + 'docker run myImage')
