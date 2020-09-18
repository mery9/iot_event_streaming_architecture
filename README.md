# IoT Event Streaming Architecture
Internet of Things (IoT) and Event Streaming at Scale with Apache Kafka and MQTT


## Used technology

* Spring Boot 2.3.3 / Apache Maven 3.6.3.
* Spring Boot Starter Actuator.
* Kafka Streams.
* Spring Kafka.
* Micrometer Registry Prometheus.
* Eclipse Paho MQTT Client.
* Kafka Connect.
* lombok.
* Jackson.

## Running Applications as Docker containers.

### Rake Tasks

The available tasks are detailed below (rake --task)


| Task | Description |
| ------ | ------ |
| check_deployment_file_task | Check Deployment File |
| check_docker_task | Check Docker and Docker Compose Task |
| cleaning_environment_task | Cleaning Evironment Task |
| deploy | Deploys the Covid Tweets Architecture and laun... |
| login | Authenticating with existing credentials |
| start | Start Containers |
| status | Status Containers |
| stop | Stop Containers |
| undeploy | UnDeploy Covid Tweets Architecture |


To start the platform make sure you have Ruby installed, go to the root directory of the project and run the `rake deploy` task, this task will carry out a series of preliminary checks, discard images and volumes that are no longer necessary and also proceed to download all the images and the initialization of the containers.

## Some screenshots

### Deploy with Docker Compose.

<img width="auto" src="./screenshots/platform_containers.PNG" />
