# docker-tomcat-sample
dockerfile and docker-compose file to run tomcat application

# Steps to run

  - build docker image using **Dockerfile** (Replace Maintainer in the file to your name-email)
    ```docker build -f Dockerfile . ```
  - list docker images and find image_id for the image you just built
    ```docker images ```
  - create a repository on docker hub
  - tag the image using 
    ```docker tag <image_id> username/reponame ```
  - push the docker image (if you are not logged in, run ```docker login``` first
    ```docker push ```
  - I have created a **docker-compose.yml** file.
  - Start and serve the docker container using
    ```docker-compose up```



### Notes
 - To run this you need docker installed on your system and drive share enabled.
 - You need an acocunt on docker hub.
 - To run your code replace the folders **WEB-INF** and **META-INF** and files **index.html** and **home.jsp**
