# Create a NodeJS app, wrap it in a docker container, and access it using Browser ( Not Deploying tho)

## 1. Create Node JS WebAPP
### Node Server setup
- Look at simple-web for index and dependency file

## 2. Create a DockerFile
### Copy Files from my local folder to inside container
- COPY <path_to_folder_on_local_file_system>  <path_to_inside_container>


## 3. Build Image from DockerFile
- "docker build -t <your_docker_id>/simple-web:1.0 "


## 4. Run Image as container
### Port forwarding and running (forward 
- "docker run -p <your_port>:<port_in_container> <image_name>"
###	Specify Workdir
- "WORKDIR <PATH_TO_WORKDIR>"



## 5. Connect to webapp from Browser
### Go to web browser
-	localhost:8080




