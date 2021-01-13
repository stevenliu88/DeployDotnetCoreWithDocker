Source tutorial:

https://www.youtube.com/watch?v=f0lMGPB10bM - Les Jackson

1. dotnet new webapi -n dockerapi -f netcore2.1 
  - Create new dotnet core 2.1 application. Name as dockerapi

2. Create Dockerfile and .dockerignore. 

3. docker -v 
check docker version 

4.open docker desktop and run docker build -t steven88docker/dockerapi

5. docker images - check image  
   docker ps - check process status
   Open docker hub that will generated automatically

6. docker run -p 8080:80 steven88docker/dockerapi - run docker container

7. docker stop "CONTAINER ID"

8. docker login by using docker hub account and password to avoid access denied when we used docker push later

9. dockert  push steven88docker/dockerapi

10 Create container instanse in Azure portal 