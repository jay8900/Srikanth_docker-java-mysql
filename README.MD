

# Dockerize java mysql project

![preview image](https://raw.githubusercontent.com/mixaverros88/docker-with-java-and-mysql/master/icons/docker_overview.JPG)
This simple example combines 2 docker files and docker-compose file, one to spin up a mysql container and the other a java container.

These docker files are located in the corresponding folders (mysql, java). Also contains a docker-compose file in the root folder.

Also you can find a network folder, which contains an sh file to create a network in order to allow the communication between the containers throughout containers names.
***
### Docker Compose
At the root file run the following command 
```
docker-compose up -d
```
After visit the following url
```
http://localhost/RESTfulExample/rest/hello/Test
```
