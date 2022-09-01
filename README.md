# Getting Started
Navigate to http://localhost:8080/graphql/schema.json 
to see the implementation copied from 
[Official Udacity Exercise Gitlab-Repo](https://gitlab.com/videolearning/udacity-java.git)

### Versions and Dependencies
Spring Boot 2.1.6.RELEASE, using 
* graphql-spring-boot-starter (5.0.2), together with 
* graphql-java-tools (5.2.4)

... requiring the use of the interfaces GraphQLQueryResolver and GraphQLMutationResolver (test)

### Example Query

Navigate to http://localhost:8080/graphiql and place following query:
```
{
    findAllLocations {
        name
    }
}
```

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.3/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.3/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.7.3/reference/htmlsingle/#web)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

