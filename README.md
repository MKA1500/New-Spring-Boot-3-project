start app, in the root folder:

docker run -p 8080:8080 -d  my-new-spring-project

stop:

docker stop {imageId}

to create an application.jar file:

mvn clean package

