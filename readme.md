# Check Docker and Docker-compose availibilty, checking version-
	- docker -v
	- docker-compose -v

# Check Docker images and container
	- docker images -a
	- docker ps -a

# To remove docker image and docker container
	- docker rmi [IMAGE ID]
	- docker rm [CONTAINER ID] -f

# To create docker image of your project
	- docker-compose build

# To containarized built docker image
	- docker-compose up

# To start, stop, down all up an running container in orchestrator
	- docker-compose start
	- docker-compose stop
	- docker-compose down

# To start, stop, down a single container from multiple container
	- sudo docker container stop [NAME]



### Note: If you do not connection to docker group user, you will need to simply use 'sudo' before running the above command.
