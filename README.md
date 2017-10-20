# Docker-Ubuntu
Repository contains Dockerfile to build various container images based on Ubuntu 

# Check if Docker is installed or not
 
$ sudo apt-get update

$ sudo apt-get install docker-ce
 
$ sudo /etc/init.d/docker restart

# For Nodejs

Dockerizing a Node.js application Dockerfile is attached. Run the two commands given below into the folder

$docker build -t nodeapp 

$docker run -p 3000:3000 nodeapp

nodeapp is the folder containing the dockerfile and the node-webapp folder

Open Web Browser- localhost:3000
