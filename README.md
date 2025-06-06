# QUIZ-APP using MICROSERVICES 
Simple QUIZ-app project developed using spring-boot that supports Microservices.

## Used Technologies:

* Back-end: Spring (Boot, Data), JPA / Hibernate, PostgreSQL, Eureka, Feign
* REST API
* Server Build: Maven

## Installation

1. Install maven: [link](https://www.baeldung.com/install-maven-on-windows-linux-mac)
2. Install Java 21: [link](https://www.oracle.com/ru/java/technologies/javase/javase8-archive-downloads.html)
3. Install Intellij IDEA Ultimate: [link](https://www.jetbrains.com/idea/)
4. Install Postgresql: [link](https://www.postgresql.org/download/)
5. Open pgAdmin and create a new DB (name: perfume and perfumetest) in Postgresql: [link](https://www.guru99.com/postgresql-create-database.html#:~:text=PostgreSQL%20Create%20Database%20using%20pgAdmin)
6. Add Postgresql properties to the application.properties file.(change Username,Password,Portnumber acoording to your pgadmin setup)
7. Create Schema in the database.(Use AI tools to generate data to insert into database using the Question and Quiz classes).
8. Run the service-registry to create a eureka server
9. Run the other three projects to send REST-API requests.