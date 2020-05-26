# SpringBoot-LDAP-Authentication
Authenticating a User with LDAP in Spring Boot


To run locally:
build and run spring boot application:
```bash
SpringBoot-LDAP-Authentication$ gradle build

SpringBoot-LDAP-Authentication$ java -jar build/libs/authenticating-ldap-0.0.1-SNAPSHOT.jar
```


 When the application starts hit http://localhost:8080
 
 You will see login page. Enter username as `ben` and password as `benspassword`. You will get login and get access to the welcome message on home page.
 
 
 
To run with Docker:
Create image
```bash
SpringBoot-LDAP-Authentication$ docker build -t spring-boot-ldap .
```
Run image in container
```bash

SpringBoot-LDAP-Authentication$ docker run -p 8080:8080 -t spring-boot-ldap:dev
```

Docker image URL at https://hub.docker.com
```bash

SpringBoot-LDAP-Authentication$ docker pull pradeep2987/spring-boot-ldap:dev
```



