### Host a Webpage with Nginx Container

**Build Image**
`docker build .`

**Build an Image with a tag**
`docker build -t hello-docker .`

**Execute the image to create a container**
`docker run -d -p 80:80 hello-docker`

Visit http://localhost:80


-----------------------------------

**View Images**
`docker images`

**View Containers**
`docker ps`

**Stop Container**
 `docker stop <container-name>`

**Remove Container** 
`docker rm <container-name>`

**Remove Image**
`docker rmi hello-docker`
