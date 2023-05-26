<p align="center">
  <img src="annie-spratt-QBvTMPAai_M-unsplash.png" alt="Cinema App" width="200">
</p>

<h1 align="center">CINEMA - APP</h1>



<sub>   
	
	"Cinema is a matter of what's in the frame and what's out.
	Martin Scorsese
	
 </sub>

The application is built on Hibernate and Spring frameworks, using REST, SOLID, DRY principles, Three-Tier architecture:

- Controllers - user interaction with the program: sending requests and receiving responses;
- Services - business logic;
- Data access object (DAO) - interaction of the program with the database.


### ⭐️ FEATURES ⭐️
>
> __In the role of `USER` you can :__
>
  > - view a list of movies
  > - view a list of cinema halls
  > - view available movie sessions
  > - create shopping cart
  > - add tickets to the shopping cart
  > - view shopping cart
  > - make an order
  > - view order history
  > 
 > __In the role of `ADMIN` you can:__
>
   > - view the list of movies and add a movie to the list
   > - add info about cinema halls
   > - delete movie session by id
   > - view the list of movie sessions and add a movie session to the list
   > - find user by email



### 🚀 STRUCTURE 🚀
>
>- config - app's configuration
>
>- dao - Data Access Object interfaces and their implementations
>
>- dto - Data Transfer Object
> 
>- exception - custom DataProcessingException
>
>- lib - email and password validators with custom annotations
>
>- model - models that represent entities in the database
>
>- service - services and their implementations that embody business logic
>
>- util - contains a DateTime pattern
>
>- resources - files with database configuration
>
>- controller - controllers for endpoints:

- `POST /login` - authentication
- `GET /logout` - logout


__AuthenticationController:__

- `/register` - new user registration

__CinemaHallController:__

- `/cinema-halls/` - show all cinema-halls
- `POST /cinema-halls/` - add a new cinema hall (`ADMIN` role)

__MovieController:__

- `GET /movies/` - show all movies
- `POST /movies/` - add a new movie ( `ADMIN` role)

__MovieSessionController:__

- `GET /movie-sessions/available/` - show all available movie sessions
- `POST /movie-sessions/` - add a new movie session (`ADMIN` role)
- `PUT /movie-sessions/${id}/` - update a movie session by id (`ADMIN` role)
- `DELETE /movie-sessions/${id}` - update/delete a movie session by id (`ADMIN` role)

__OrderController:__

- `GET /orders/` - show user's order history
- `POST /orders/complete` - complete order

__ShoppingCartController:__

- `GET /shopping-carts/by-user/` - show all tickets added to user's shopping cart
- `PUT /shopping-carts/movie-sessions/` - update shopping cart by movie session id

__UserController:__

- `GET /users/by-email/` - show user's information by email (`ADMIN` role)


### 💡 TECHNOLOGIES 💡
> - **Maven** `v.3.10.1` - build tool and dependency management
> - **JDK** `v.17.0.2` - Java Development Kit
> - **Spring Core** `v.5.3.20` - core framework of Spring
> - **MySql** `v.8.0.22` - relational database management system
> - **Hibernate** `v.5.6.14.Final` - object-relational mapping (ORM) for working with the database
> - **Hibernate Validator** `v.6.1.6.Final` - data validation using Hibernate annotations
> - **Jackson core** `v.2.14.1` - library for working with JSON
> - **Javax annotation** `v.1.3.2` - standard Java annotations
> - **Java Servlets API** `v.4.0.1` - extension for building Java-based web applications
> - **Tomcat** `v.9.0.73` - server for deploying Java web applications


 <a href="https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-compiler-plugin/3.10.1">
    <img src="https://maven.apache.org/images/maven-logo-black-on-white.png" alt="Maven" width="100" height="50">
</a>

<a href="https://www.oracle.com/java/technologies/javase-jdk17-downloads.html">
    <img src="https://img.shields.io/badge/JDK-v.17.0.2-orange" alt="JDK" width="100" height="50">
</a>

<a href="https://spring.io/projects/spring-framework">
    <img src="https://img.shields.io/badge/Spring%20Core-v.5.3.20-brightgreen" alt="Spring Core" width="150" height="50">
</a>

 <a href="https://dev.mysql.com/downloads/mysql/8.0.22.html">
    <img src="https://img.shields.io/badge/MySQL-v.8.0.22-blue" alt="MySQL" width="100" height="50">
</a>

<a href="https://hibernate.org/orm/">
    <img src="https://img.shields.io/badge/Hibernate-v.5.6.14.Final-lightblue" alt="Hibernate" width="200" height="50">
</a>

<a href="https://github.com/FasterXML/jackson-core">
    <img src="https://img.shields.io/badge/Jackson%20Core-v.2.14.1-yellow" alt="Jackson Core" width="150" height="50">
</a>

<a href="https://mvnrepository.com/artifact/javax.annotation/javax.annotation-api/1.3.2">
    <img src="https://img.shields.io/badge/Javax%20Annotation-v.1.3.2-red" alt="Javax Annotation" width="200" height="50">
</a>


<a href="https://mvnrepository.com/artifact/javax.servlet/javax.servlet-api/4.0.1">
    <img src="https://img.shields.io/badge/Java%20Servlets%20API-v.4.0.1-blueviolet" alt="Java Servlets API" width="200" height="50">
</a>

<a href="https://tomcat.apache.org/download-90.cgi">
    <img src="https://img.shields.io/badge/Tomcat-v.9.0.73-yellowgreen" alt="Tomcat" width="200" height="50">
</a>

<a href="https://hibernate.org/orm/"><a href="https://hibernate.org/validator/">
    <img src="https://img.shields.io/badge/Hibernate%20Validator-v.6.1.6.Final-lightblue" alt="Hibernate Validator" width="300" height="50">
</a>





### 💬 Contact 💬
	
[Kazanivska Sofiia](https://www.linkedin.com/in/sofiia-kazanivska-40a413232/) <br>
sofiakazzz@gmail.com



