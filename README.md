# testConfigServer
Part of a spring cloud sample 
Tutorial link : https://www.youtube.com/watch?v=ZyK5QrKCbwM

## Config Server 
The config services are in a  remote repository who Josh Long developed and shared as a part of his tutorial which this project is based on
## Requirements 
- Spring boot
- java 8
- Remote git repository : https://github.com/joshlong/bootiful-microservices-config
## Dependencies
	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-config-server</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>
  *** Actuator dependency is optional on new versions of spring cloud 
## Run
Run the main class as a Spring boot app 
## Query
http://localhost:8888/config-service/master
