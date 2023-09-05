# Class 13

## **Related data in Spring **
   1. Name a few real life examples of “One-To-Many” relationships.
      - Author and Books: One author can write many books, but each book has only one author.
      - Country and Cities: A country can have multiple cities, but each city belongs to one country.
      - Parent and Children: One parent can have multiple children, but each child has only one set of parents.
      
   2. Given two entities, one named Player and one named Team, if you wanted to create a one-to-many relationship 
      with those entities which would be the one and which would be the many?
      **"Team" can have many "Players," while each "Player" belongs to only one "Team."**
      Many: Players
      One: Team
   3. Explain one-to-many relationships to a non-technical friend.
      Library and Books Example:
      Imagine you have a library with shelves and books. In this case:

    The "shelves" are like the "Teams."
    The "books" are like the "Players."

In a "One-to-Many" relationship:

    Each shelf (Team) can hold many books (Players). You can have a shelf for science books, another for fiction, and 
    so on. However, each book (Player) belongs to only one shelf (Team). For instance, a Harry Potter book belongs to 
    the fiction shelf, and a biology textbook belongs to the science shelf.
    "One-to-Many" relationship in the library means you can have many books on each shelf, but each book is only on 
    one shelf.


## **Baeldung: Spring Integration Testing**

   1. Describe the difference between a unit test and an integration test.
      - Unit Test: A unit test is focused on testing a small, isolated piece of code, typically a single class or method. 
        It aims to ensure that individual units of code (like functions or methods) work correctly in isolation. 
        Unit tests often use mock objects or stubs to isolate the unit being tested from external dependencies.
      
      - Integration Test: An integration test, on the other hand, is concerned with verifying that different components
        or modules of an application work together correctly as a whole. It tests the interactions and integrations
        between various units or modules, potentially involving databases, external services, and other components. 
        Integration tests ensure that the application's parts function correctly together.

   2. What is the object that provides support for Sprin MVC Testing?
      `MockMvc` class.
      allows you to simulate HTTP requests to your Spring MVC controllers, perform those requests, and then make 
      assertions about the responses. It provides a way to test your controllers in isolation without actually making 
      real HTTP requests to your application.

   3. What does the “perform()” method do in a Spring integration test?
      is used to simulate an HTTP request and perform it against a particular controller endpoint. This method allows
      you to specify the HTTP method (GET, POST, PUT, DELETE, etc.), set request parameters, add request headers,
      and send the request to the specified endpoint.


## Things I want to know more about
To dive deeper into the topics of unit testing, integration testing, Spring MVC testing, and related concepts.
