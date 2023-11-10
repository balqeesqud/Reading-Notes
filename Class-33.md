# One-To-Many / Many-To-One Relationships In GraphQL And DynamoDb

 1. Describe asynchronous actions in your own words.
   `Asynchronous actions refer to operations or tasks in a program that do not occur in a synchronous, blocking manner.
   Instead of executing sequentially one after another, asynchronous actions allow the program to initiate a task and
   continue with other operations without waiting for the completion of the initial task. The program can later return 
   to the initial task once it is finished. Asynchronous programming is particularly useful for operations that may take
   time to complete, such as network requests, file I/O, or any task where waiting for completion could lead to 
   performance issues or unresponsiveness.
   In the context of Java, asynchronous actions are often implemented using features like CompletableFuture or
   callbacks. These mechanisms enable a program to execute tasks concurrently, improving overall efficiency and 
   responsiveness.`

 2. What is the benefit of asynchronous methods?
    - **Improved Responsiveness:** Asynchronous methods prevent the program from blocking and waiting for a particular
      task to complete. This helps maintain the responsiveness of the application, especially when dealing with 
      time-consuming operations like network requests or file I/O.
    - **Concurrency:** Asynchronous methods allow multiple tasks to be executed concurrently, taking full advantage of 
      available system resources. This can lead to improved performance and faster execution of tasks.
    - **Resource Utilization:** By not blocking the execution while waiting for a task to complete, other parts of the
      program can continue their execution, effectively utilizing available resources.
    - **Enhanced User Experience:** In applications with a user interface, asynchronous methods can prevent the 
      interface from freezing during resource-intensive operations, providing a smoother and more interactive user 
      experience.


## Things I want to know more about

- Relational Data Modeling:
  1. Understand the concepts of one-to-many and many-to-one relationships in the context of data modeling.
  2. Explore normalization and de-normalization strategies.


- DynamoDB and Relationships:
  1. Explore how DynamoDB supports or models relationships.
  2. Learn about strategies for handling relationships in NoSQL databases.

- Optimizing for Performance:
  1. Understand how to optimize queries and data retrieval for performance.
  2. Explore techniques such as batching and caching.