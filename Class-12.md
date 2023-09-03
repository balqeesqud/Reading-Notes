# Class 12

## **Spring guide: Accessing Data with JPA**

  1. How are query methods defined when using Spring Data JPA?
     by simply creating method signatures in the repository interface. The method names follow a specific naming 
     convention, such as findByPropertyName, findByPropertyNameAndOtherProperty.

  2. Which dependencies will you need in order to complete the Spring guide?
     - spring-boot-starter-data-jpa: This starter includes Spring Data JPA and Hibernate for ORM.
     - A database driver dependency like PostgresSQL.
     - Spring Boot starter dependencies appropriate for your application (spring-boot-starter-web for a web 
       application).
     - It may need additional dependencies depending on the project requirements.
     
  3. What annotations are used to specify an auto generated identification number for an Entity?
     Using @Id and @GeneratedValue annotations. 
 

## **Baeldung: Comparing repositories** 

  1.  Which of the Spring Data Repositories covered in the readings has the most methods available to it?
      - JpaRepository typically has the most methods available. This is because JpaRepository extends the 
        CrudRepository and adds additional JPA-specific methods for performing CRUD (Create, Read, Update, Delete) 
        operations on entities.
      
  2.  Name a downside of a Spring Data Repository.
      it abstracts away some of the low-level details of database interactions. While this abstraction can make 
      development faster and easier, it can also lead to performance issues if developers are not aware of how specific 
      queries are executed in the underlying database.

  3.  How would you define an operation to find a student based on their name in a repo named StudentRepository which
      extends JpaRepository?
      By defining a query method in the StudentRepository interface to find a student based on their name. Assuming to 
      have a Student entity with a name attribute.
    