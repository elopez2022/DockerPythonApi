# DockerPythonApi
Sample Docker Linux Container with Rest Api Route

## Docker Commands ##
### Build ###
````
docker build -t simple-python-api:0.0.1 .
````
### Run ###
````
docker run -p 8000:8000 simple-python-api:0.0.1
````
### Get Docker Container(s) Information ###
````
docker ps
````
### Stop ###
````
docker stop <container id> or <container name>
````
### Start ###
````
docker start <container id> or <container name>
````
#### Test Container ####
````
http://localhost:8000/Bob or http://localhost:8000/Bob Smith
````
