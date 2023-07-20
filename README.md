# MyAppMarina BackEnd SpringBoot Java 8

This project was generated with [SpringBoot](https://spring.io/projects/spring-boot/) version 2


A apricação esta divida entre o back e front 
e nessecario subir  subir as duas parte 


## To deploy the application run the commands

##To deploy of FRONT   run the commands in go to folder ----Front-Angular----- PART 1
## run this command below:
docker build -t ng-docker-app:v1.0.0 -f ./Dockerfile .

## after creating the img run this command below:
docker run -p 8000:80 -d ng-docker-app:v1.0.0

## after up image go on
[MyAppMarina](http://localhost:8000/)


##To deploy of BACK run the commands in go to folder BACK ----Back-Java-Spring-Boot----- PART 2 final

## Run this command below:
docker-compose up -d

## Attention ports used by the system

the ports listed below must not be used for the application to deploy correctly<br />
<br />
8765 - gateway<br />
5055 - core<br />
5051 - oauth2<br />
8761 - registre eureka<br />
5432 - postgresSQL  <br />
8000   - front-end aplication<br />


## after creating the img system up online in average 3 minutes:

after uploading the images, two default emails will be produced to access the application <br />
	the admin: <br />
	login= admin@todo.com <br />
	password = 123456 <br />
	for user: <br />
	login= test <br />
	password = 123456 <br />

## Document of system is Swagger in localhots 8765

go after up system<br />
[Swagger](http://localhost:8765/core/swagger-ui/index.html)<br />
<br />
or in <br />
<br />
[Swagger direct](http://localhost:5055/swagger-ui/index.html#/)<br />

## Further help

talk to me  https://www.linkedin.com/in/marina-oliveira-395720160/
