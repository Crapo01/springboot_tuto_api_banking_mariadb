# BANKING API MARIADB

eclipse with springboot initializer

java project, maven

dependencies:
Spring web  
Spring Data Jpa
PostgreSQL Driver
Lombok


##source:

 https://www.youtube.com/watch?v=vpf4LB54rVw

## application.properties

https://www.cdata.com/kb/tech/mariadb-jdbc-spring-boot.rst

//connect to db  

spring.datasource.url=jdbc:mariadb://localhost:3306/banking  
spring.datasource.username=root  
spring.datasource.password=  
spring.datasource.driver-class-name=org.mariadb.jdbc.Driver    

//auto create tables  

spring.jpa.hibernate.ddl-auto=update  




