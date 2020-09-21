
In this app, I used H2 in-memory database
**To Run without Docker**

```
> mvn clean install
> java -jar target/TelenorAssignment-0.0.1-SNAPSHOT.jar
```

**To Run with Docker**
```
> mvn clean install
> docker build -t springio/gs-spring-boot-docker .
> docker run -p 8080:8080 -t springio/gs-spring-boot-docker

> docker stop <image-name>
```
