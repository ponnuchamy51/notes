Docker

docker images - To view docker images

docker run -it ubuntu

docker ps  - To view the active containers

docker ps -a - Both containers are no longer running, but they still exist on your system

docker ps -l - view the latest container you created

docker start 

docker stop 

docker rm CONTAINER_ID

docker commit -m "added Node.js" -a "sammy" d9b100f2f636 sammy/ubuntu-nodejs


docker login -u docker-registry-username

docker tag sammy/ubuntu-nodejs docker-registry-username/ubuntu-nodejs

docker push sammy/ubuntu-nodejs
