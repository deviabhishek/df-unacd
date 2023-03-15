Dockerfiles
Dockerfile is a declarative way of creating our own images. Docker will give us some syntax to create our own images.

File name should Dockerfile. docker command should run where your Dockerfile exists.

How to build image from Dockerfile

docker build -t [docker-hub-URL]/[your-username]/[image-name]:version .
Ex:  docker build devops/from:v1 .
     devops = my github username
     from = my imagename
     vi = my version name
     . = dot is mandatory because it represent your your build image current directory 
                  or
          it is your current direactory        
     
Before pushing to docker hub it asking you it login
 $ docker login
   user: devops
   pass: give your git hub password



How to push image to Dockerhub
docker push [docker-hub-URL]/[your-username]/[image-name]:version

docker push devops/from:v1

xxxxxxx==================xxxxxxxxxxxxx=======================xxxxxxxxxxxxxxxxxxx==============================xxxxxxxxxxxxxxxxxxxxxxx
