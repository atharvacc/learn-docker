# Some basic commands

### docker run <image_name>
- ex: docker run hello_world
- downloads image if doesn't exist on docker.
- makes container with relevant resources 
- runs the default command
- run = create (create container) + start ( start an image)

### docker run <image_name> <default_command_override>
- ex : docker run busybox echo hi there
- Overrides defualt command with "echo hi there"

### docker run <image_name> ls
- list out stuff inside the image that the hardware segments

### docker ps 
- List running containers on machine

### docker ps --all
- List of all containers we have ever created

###  docker create <image name>
- Create a container from an image

### docker start <container_id> 
- Start container
- No output shown unless parameter explicitly added  
- "-a" - watch for output and print it out

### docker system prune
- Delete stopped containers
- Delete Build Cache
- Remove images
	
### docker logs <container_id>
- Get output if you forgot to add "-a" to start to get output printed out

### docker stop <container_id>
- Send hardware signal to stop 
- Little time to do cleanup 
- Gives about 10 secs to stop, and then issues kill

### docker kill <container_id>
- Send SigKill to stop the container

### docker exec -it <container_id> <command we want to execture>
- Execute a command inside container 
- "-it" type input into the container id
- "-it" more or less takes input to the container and fetches output to our screen

### docker exec -it <container_id> sh
- get shell access to container

### docker run -it <image_name> sh
- get shell access while using the run command


### 

