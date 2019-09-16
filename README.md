# Spring Books REST api

## Request
Management has requested that we expose our book database with a RESTfull api so that they can 
test writing a front end management tool. They have asked that we do this quickly.

## Database
This is the definition of a book. You will build a `Book` entity in your Spring application. *You should not need to manually add this table to MySQL, the application should do it for you when configured properly.*

```
CREATE TABLE `books` (
  `id` bigint(20) NOT NULL AUTO_INCREMENT,
  `title` varchar(255) NULL,
  `author` varchar(255) NULL,
  `genre` varchar(255) NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=335 DEFAULT 
```

## Technologies
* Spring Boot
* Spring JPA
* Spring WEB
* MySQL database

## User Stories
1. add books to the system
1. retrieve all books for a given genre.
1. retrieve ALL the books in the system
1. retrieve a book by their id

## Getting started
1. Create a MySQL db named 'springbooks_db'
1. Note: this is a 'gradle' project so your ide must support gradle
1. Implement the controller, service, entity and repository for `Book`.

*NOTE: Write your tests first!*

## Resources
[Test Driven Development with Spring Boot](https://www.youtube.com/watch?v=s9vt6UJiHg4)

