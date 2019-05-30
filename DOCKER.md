## DOCKER

# Check docker version
docker -v     OR    docker --version

# Get active running containers
docker ps

# Get active and inactive containers
docker ps -a

# List images
docker images

# Remove image
docker rmi imageId
 
# To start container
docker run imageName
  
# To start stopped container
docker start containerId

#  To stop the running container
docker stop containerId

# Ip address of the container
docker inspect containerId

# Get disk usuage space of docker
docker system df

