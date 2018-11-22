# docker-elk-stack

- This is just a sample docker-compose file for starting work on the Elasticsearch, Logstash, Kibana (ELK) Stack for data analysis.

- Setting up individual servers on the system is a troublesome process. In the agile development environment one cannot waste time in setting 
up the ELK environment.

- Docker provides a good method for provisioning an isolated environment but having multiple containers and linking them is an issue. The docker-compose file associated with this repo is used for creating an ELK stack with persistence and working under the same network.

- SAMPLE COMMANDS TO WORK WITH THE FILE ARE
	- docker-compose up :   to create the volumes, network and ELK containers.
	- docker-compose down:  to delete the volumes, network and ELK containers. Data will not be persisted.
	- docker-compose stop:  to stop all the containers specified under the compose file. Data will be persisted.
	- docker-compose start: to start all the stopped containers.
