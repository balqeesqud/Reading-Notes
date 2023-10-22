# Room 


1. What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?
   Room. Yes, it's a good choice
   The Room persistence library provides an abstraction layer over SQLite to allow fluent database access while 
   harnessing the full power of SQLite. In particular, Room provides the following benefits:
   - Compile-time verification of SQL queries.
   - Convenience annotations that minimize repetitive and error-prone boilerplate code.
   - Streamlined database migration paths.

2. Do Rooms have any similarities to JPA?
   Yes, Room and JPA (Java Persistence API) share some similarities because they both deal with data persistence and 
   mapping of objects to a relational database. they are both designed for different platforms and have some distinct
   characteristics.
   Similarities: 
   - **Object-Relational Mapping (ORM):** they provide mechanisms for mapping Java objects to database tables.
   - **Annotations:** Both use annotations to define how data objects (Java classes) correspond to database entities (tables).
   - **Entity Classes:** defining entity classes to represent database tables. 
     These classes typically have fields that map to table columns.
   
3. Describe a DAO in your own words
   Stands for a Data access object, and it's one of the major components in the Room, that provide methods that an app 
   can use to query, update, insert, and delete data in the database.
   The app can use the **DAOs** to retrieve data from the database as instances of the associated data entity objects.
   In essence, a DAO acts as a bridge between the application and the database, offering a structured and consistent 
   way to manage data. 
