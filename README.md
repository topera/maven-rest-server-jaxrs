# Topera's Hello World #002
## Rest Server with Maven (using JAX-RS)
This hello world is a Rest Server

How to test
* $ cd maven-rest-server-jaxrs
* $ mvn package
* Get generated war from ./target and deploy it.
* This example is configured to have a context root in "/", in JBoss. So, to test, please access: http://localhost:8080/api/test
* In other servers, access: http://localhost:8080/hello.maven.rest-1.0/api/test

Tech Stack
* Intellij IDEA 2016.1.4
* Maven 3.5.0
* Java 8

To take a look in other projects, please see https://github.com/topera/index
