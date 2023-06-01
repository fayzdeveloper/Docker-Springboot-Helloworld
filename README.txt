This is a Dockerized simple spring boot application with a single rest endpoint(http://localhost:8080/rest/docker/hello)
#Open the project in Injellij idea
#Build the project using the command: "docker build -t springboot-docker-hello:1.0 ."
    where -t specifies the tag name(image name)
#To list all the docker images, run "docker images"
     #Run the docker image using the command: "docker run -p 8080:8080 springboot-docker-hello:1.0"
     #Once the application is started, make a GET request to "http://localhost:8080/rest/docker/hello".
     #It will return a string "Hello Docker!"
 Cheers!
