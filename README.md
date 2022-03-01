# configserver is no longer actively maintained by VMware, Inc.

# Spring Cloud Config Server for Configuration Samples

To startup a Spring Cloud Config Server, run this project as a Spring Boot app by issuing:


```
$ ./mvnw spring-boot:run
```

or

```
$ ./mvnw package
$ java -jar target/*.jar
```

It will start up on port 8888 and serve configuration data from
"https://github.com/steeltoeoss/config-repo":
