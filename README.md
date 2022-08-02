# onlinebookstore
REST API for an online bookstore, where the user can perform the following operations:
CRUD operations on Books
Checkout operation for single or multiple books which will return the total payable amount.

***Technology :*** 

Java 11 
spring-boot 2.4.5
Database : In memory H2
mvn 3.2.x
Server : Embedded Tomcat

CREATING/RUNNING JAR 

    *$ git clone https://github.com/arunima-nair/onlinebookstore.git
    $ mvn clean
    $ mvn install*

Open API documentation : *http://localhost:8080/v2/api-docs*
Swagger auto generated API documentation URL : http://baseurl:port/swagger-ui.html#/ *[  http://localhost:8080/swagger-ui.html  ]*

Creating/run docker image

    $ docker build ./
    $ docker images
    $ docker run -it -p8080:8080 <image-id>
