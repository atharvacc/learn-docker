# How to build your own customer Docker image using docker Server
## Basic idea
## Docker File (Plain text file for configuration; define how our container behaves) -> Docker Client (Docker CLI) -> Docker Server( Build a usable image) ->	Image file
 
### Example

Check out the redis-image folder and the docker file inside of it.

Go to the folder and run "docker build ." 


## Build image out of running container
-	 Run image , and do whatever,
-	 go to different, terminal, and get the id of the running process
-	"docker commit -c 'CMD['<default_command>']'	<id_of_running>	"
