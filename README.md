# Important
<pre>
1. Install docker app
2. Install node
</pre>


# Commands to create your own container

### Important commands
<pre>
1- docker build -t leo/docker-node . (creates the image)
2- docker run -p 3000:3000 -d leo/docker-node (runs the image)
3- open localhost:3000 (see the container running)
4- docker-compose up (runs container)
</pre>

### Helpers:
<pre>
docker ps (show the running containers)
docker ps -a (show all containers)
docker images (show all images)
</pre>
