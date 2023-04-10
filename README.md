** Docker Commands **
>docker version
>docker info
>docker run hello-world 
(This is short lived container)

>docker ps
>docker ps -a


Docker Client --> Docker Daemon --> HOST (Local Store)<br/>
                                ----> DockerHub-|  <br/>
                            <----------PULL-----|          
>docker images

** How to create container from docker image **
>docker pull <alpine>
>docker run -it <alpine>
<br/>
#ls
<br/>
#exit

** Start Exited container again**
>docker start -i <Container_ID>


** How to delete an image**
docker image rmi -f <image_name/repository>