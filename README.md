# Spring Boot - Accessing and Adding Data

## Dependencies

- Spring Web
- Spring Data JPA
- H2 Database
- Spring Boot Dev Tools
- Thymeleaf

### Dependencies

Had to update my Java version in pom.xml to 1.11 to make my local JDK

### App Properties

Added a few lines to be able to access our H2 database through console and to be able to load a external SQL source

### JPA

JPA - Java Persistance API
Collection of methods and classes for storing data in a database
Where does it come from?

- Dependency: Spring Data JPA

#### Annotations

- @Entity - designates a POJO class as an entity so that we can use it with JPA
- @Id - JPA will recognize this as the object's primary key
- @GeneratedValue - allows the database to set the value for the field
- @Column - attribute is stored in a database column by the same name
- @CreationTimestamp - sets the value of the field to the current time and date during creation (exactly once)

### Thymeleaf
