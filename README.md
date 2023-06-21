# docker-nginx

Build Image
docker build .

Build Image with a tag
docker build -t hello-docker .

Execute the image to create a container
docker run -d -p 80:80 hello-docker

visit
http://localhost:80


Extra

View Images
docker images

View Containers
docker ps

Stop Container
 docker stop <container-name>

Remove Container 
docker rm <container-name>

Remove Image
docker rmi hello-docker
